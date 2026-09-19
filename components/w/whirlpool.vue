<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b8oaxdbmg"/><circle class="pw_8zeien"/><path class="x0olepcje"/><path class="ojnhmt8wq"/><path class="yjm1qhb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whirlpool" /></template>
<style>
.b8oaxdbmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.38 26.313a1.65 1.65 0 0 1-1.646-1.646v-1.07c0-.906.74-1.647 1.646-1.647s1.646.741 1.646 1.647v1.07a1.65 1.65 0 0 1-1.646 1.646m4.82-.001a1.65 1.65 0 0 1-1.646-1.647v-1.07c0-.905.74-1.646 1.646-1.646h0c.905 0 1.646.74 1.646 1.646v1.07a1.65 1.65 0 0 1-1.646 1.646m-15.904-2.844c0-.906.741-1.647 1.647-1.647m-1.647 0v4.363");
}

.ojnhmt8wq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.333 20.843c2.895-1.867 5.368-2.74 5.805-2.452c3.245 1.823-9.392 13.164-11.825 10.998c-.565-.407-.173-1.891.976-3.705");
}

.pw_8zeien {
  cx: 19.394px;
  cy: 19.861px;
  r: 0.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x0olepcje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.394 21.837V26.2m4.657-6.563V25.4c0 .494.33.824.824.824h.247m15.308-6.625v5.762c0 .494.33.823.823.823h.247m-15.368-1.567c0 .905.74 1.646 1.646 1.646s1.646-.74 1.646-1.646v-1.07c0-.906-.74-1.647-1.646-1.647s-1.646.741-1.646 1.646m0-1.646v6.585m-13.047-8.89l-1.646 6.585l-1.646-6.585l-1.647 6.585L6.5 19.595m7.906.05v6.585m.001-2.716c0-.906.74-1.647 1.646-1.647s1.646.741 1.646 1.647v2.716");
}

.yjm1qhb_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 35.5v-23a4 4 0 0 0-4-4h-31a4 4 0 0 0-4 4v23a4 4 0 0 0 4 4h31a4 4 0 0 0 4-4");
}

</style>
