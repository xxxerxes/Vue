<template>
  <div class="demo">
    <h3>姓名：{{ name }}</h3>
    <h3>年龄：{{ age }}</h3>
    <button @click="show">点我</button>
  </div>
</template>

<script>
export default {
  name: "School",
  data() {
    return {
      name: "xx",
      age: 18,
    };
  },
  methods: {
    show() {
      alert(this.name);
    },
  },
};
</script>

<style>
.demo {
  background-color: orange;
}
</style>