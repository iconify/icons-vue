<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vmv83ubqx"/><path class="r0i3sy48f"/><circle class="ralvlywcn"/><circle class="cjpl_kbnp"/><path class="b3pti3hik"/><path class="py9exybta"/><circle class="fp0xahb-b"/><circle class="pv0u3bcyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-tamagotchi-forever" /></template>
<style>
.b3pti3hik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.532 18.237c.088.163.26.605.26.803v1.223c0 1.322-2.619 2.393-5.847 2.393h-.895c-3.23 0-5.847-1.071-5.847-2.393V19.04c0-.24.072-.464.218-.975c-.594-1.43-.434-2.532.501-3.636c3.3.411 6.64.374 9.93-.11a2.37 2.37 0 0 1 1.3.179q1.22.511.505 2.598c-.1.291-.06.839-.125 1.141");
}

.cjpl_kbnp {
  cx: 32.32px;
  cy: 11.499px;
  r: 1.169px;
  fill: none;
  stroke: currentColor;
}

.fp0xahb-b {
  cx: 33.515px;
  cy: 17.651px;
  r: 1.754px;
  fill: none;
  stroke: currentColor;
}

.pv0u3bcyz {
  cx: 13.68px;
  cy: 17.741px;
  r: 1.754px;
  fill: none;
  stroke: currentColor;
}

.py9exybta {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.417 18.066c3.66 1.182 7.826 1.108 12.034-.136");
}

.r0i3sy48f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.077 39.987l.03.405c0 1.459-1.568 2.526-3.498 2.383l-.592-.042c-1.93-.141-3.498-1.438-3.499-2.896l.031-1.352m13.955 1.147v.66c.001 1.63 1.568 2.837 3.5 2.697l.59-.043c1.932-.142 3.497-1.58 3.498-3.21v-1.542M9.874 31.56c-.548.232-.898.358-1.32.407q-2.057.245-2.096-2.404c.395-2.472 1.904-4.574 4.62-6.893c-.912-2.744-1.141-5.377-.927-8.41q.253-3.59 3.4-6.342q2.07-1.807 5.024-2.235Q25.347 3.85 32.637 6.94q4.41 1.87 4.84 8.272c.158 2.376.15 4.525-.197 6.741c2.288 1.913 3.627 4.068 4.262 6.508q-.116 2.541-2.406 2.196");
}

.ralvlywcn {
  cx: 15.154px;
  cy: 11.904px;
  r: 1.169px;
  fill: none;
  stroke: currentColor;
}

.vmv83ubqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.566 26.287q-2.145 9.358 3.12 12.184q8.95 3.027 21.642-.535q6.251-3.585 1.804-13.064");
}

</style>
