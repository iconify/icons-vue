<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r9f54xbnv"/><path class="lcu9_kuzk"/><path class="tld0unb0v"/><circle class="k3fs6wbrf"/><circle class="v2u_1g68u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:virgin-radio-switzerland" /></template>
<style>
.k3fs6wbrf {
  cx: 22.342px;
  cy: 24.188px;
  r: 0.75px;
  fill: currentColor;
}

.lcu9_kuzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.596 27.26l1.175-3.152l1.448 7.73c.527-5.387 1.765-10.054 3.846-13.866m-1.158 8.163l-.226 2.842m1.85-.956l.07-2.612l1.03-.493m1.908-1.083c-.654.103-.868 1.09-.998 1.983c-.27 1.887 1.374 1.366 2.012.41m.063-2.589l-.2 9.968m1.876-10.823l-.18 2.444m1.633-.666l.088-1.942c.605-.753 1.494-1.804 1.956-1.2c.608.794-.504 2.84.766 2.71");
}

.r9f54xbnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m3.5 19.383l15.596.002L23.888 4.47l4.828 14.917l15.784.002l-12.778 9.284l4.81 14.856l-12.59-9.204l-12.583 9.143l4.772-14.853z");
}

.tld0unb0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.745 23.786c-2.734.431-13.83 8.438-13.642 9.344");
}

.v2u_1g68u {
  cx: 29.721px;
  cy: 20.98px;
  r: 0.75px;
  fill: currentColor;
}

</style>
