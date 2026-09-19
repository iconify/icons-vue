<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a-utdgn0s"/><path class="da_tr5ien"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mon-compte" /></template>
<style>
.a-utdgn0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.545 40.015c-.166-3.932-.343-7.853 1.104-10.493s4.507-3.976 6.627-3.313s3.28 3.324 3.866 6.075c.585 2.75.585 5.577.585 8.394m7.709-15.441q.542 8.15 1.094 16.987M9.918 41.119q0-7.521-.552-15.462m-3.866 0q12.15-14.359 18.776-19.88");
}

.da_tr5ien {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.62 7.433q9.94 6.627 19.88 17.12");
}

</style>
