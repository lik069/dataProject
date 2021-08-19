<template>
  <div class="bg">
    <div class="userPass">
      <el-card class="box-card">
        <div slot="header" class="clearfix">
          <span>欢迎登录</span>
        </div>
          <div>
            <el-input placeholder="请输入内容">
              <template slot="prepend">用户名://</template>
            </el-input>
          </div>
      </el-card>
    </div>
  </div>
</template>
<script>
export default {
  name: "login",
  /**
   *
   * 数据加载
   */
  data() {},
  /**
   * 初期方法
   */
  created() {},
  mounted() {},
  methods: {},
};
</script>

<style scoped>
.bg {
  margin: 0;
  padding: 0;
}
.userPass {
  width: 480px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
.text {
  font-size: 14px;
}

.item {
  margin-bottom: 18px;
}

.clearfix:before,
.clearfix:after {
  display: table;
  content: "";
}
.clearfix:after {
  clear: both;
}

.box-card {
  width: 480px;
}
</style>