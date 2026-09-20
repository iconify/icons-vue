<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<ellipse class="v0h4t-bui"/><ellipse class="xufgvfbwi"/><path class="z5ryq4b1e"/><path class="wf-90pb3h"/><ellipse class="dp0dffe5q"/><path class="fxnun_o3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:teacup-without-handle" /></template>
<style>
.dp0dffe5q {
  cx: 18px;
  cy: 13px;
  fill: var(--svg-color--a6d388, #a6d388);
  rx: 15px;
  ry: 7px;
}

.fxnun_o3o {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M21 17a1 1 0 0 1-.707-.293c-2.337-2.337-2.376-4.885-.125-8.262c.739-1.109.9-2.246.478-3.377c-.461-1.236-1.438-1.996-1.731-2.077c-.553 0-.958-.443-.958-.996S18.448 1 19 1c.997 0 2.395 1.153 3.183 2.625c1.034 1.933.91 4.039-.351 5.929c-1.961 2.942-1.531 4.332-.125 5.738A.999.999 0 0 1 21 17m-6-2a1 1 0 0 1-.707-.293c-2.337-2.337-2.376-4.885-.125-8.262c.727-1.091.893-2.083.494-2.947c-.444-.961-1.431-1.469-1.684-1.499a.99.99 0 0 1-.989-1c0-.552.458-1 1.011-1c.997 0 2.585.974 3.36 2.423c.481.899 1.052 2.761-.528 5.131c-1.961 2.942-1.531 4.332-.125 5.738a1 1 0 0 1 0 1.414A1 1 0 0 1 15 15");
}

.v0h4t-bui {
  cx: 18px;
  cy: 26px;
  fill: var(--svg-color--292f33, #292f33);
  rx: 18px;
  ry: 10px;
}

.wf-90pb3h {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M35 12.056c0 5.216-7.611 9.444-17 9.444S1 17.271 1 12.056s7.611-8.445 17-8.445s17 3.229 17 8.445");
}

.xufgvfbwi {
  cx: 18px;
  cy: 24px;
  fill: var(--svg-color--66757f, #66757f);
  rx: 18px;
  ry: 10px;
}

.z5ryq4b1e {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M18 31C3.042 31 1 16 1 12h34c0 2-1.958 19-17 19");
}

</style>
