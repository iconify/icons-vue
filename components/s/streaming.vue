<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fj99qeb3r"/><path class="zjrnu6b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:streaming" /></template>
<style>
.fj99qeb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.394 10.855l-3.14 12.53c-.29 1.156.24 2.67 1.186 3.394l4.085 3.127c.946.724 1.941.376 2.23-.78l3.147-12.556c.491-1.961 1.16-2.75 3.427-2.75h12.922c1.242 0 1.853-.921 1.37-2.066l-1.766-4.188C39.372 6.42 37.983 5.5 36.74 5.5H24.335c-3.581 0-6.94 1.36-7.94 5.355");
}

.zjrnu6b9d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.606 37.145l3.14-12.53c.29-1.156-.24-2.67-1.186-3.394l-4.085-3.127c-.946-.724-1.941-.376-2.23.78L24.097 31.43c-.491 1.961-1.16 2.75-3.427 2.75H7.749c-1.242 0-1.853.921-1.37 2.066l1.766 4.188c.483 1.145 1.872 2.066 3.114 2.066h12.406c3.581 0 6.94-1.36 7.94-5.355Z");
}

</style>
