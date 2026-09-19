<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="amiwh3w0w"/><circle class="k7yz7t8ai"/><circle class="bs6jnhktd"/><circle class="sdh-cbbno"/><circle class="cd48341zy"/><ellipse transform="rotate(-4.12 19.677 23.605)" class="tdwhvxrli"/><path class="nnetr2dfr"/><path class="li4la8vge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-page" /></template>
<style>
.amiwh3w0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.58 22.744c0 2.342 2.342 2.159 2.342 3.381s-5.336.978-5.336 5.459s4.094 6.823 9.817 6.823s15.011-2.505 15.011-10.734s-9.573-9.206-12.75-9.206s-9.084 1.201-9.084 4.277");
}

.bs6jnhktd {
  cx: 26.882px;
  cy: 34.231px;
  r: 1.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cd48341zy {
  cx: 32.157px;
  cy: 25.27px;
  r: 1.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k7yz7t8ai {
  cx: 20.792px;
  cy: 34.863px;
  r: 1.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.li4la8vge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.228 13.667V9.3L29.66 5.733h-10.9L15.194 9.3v4.367");
}

.nnetr2dfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.933 42.267H9.067L5.5 38.7V13.667h37V38.7z");
}

.sdh-cbbno {
  cx: 31.913px;
  cy: 30.932px;
  r: 1.621px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tdwhvxrli {
  cx: 19.677px;
  cy: 23.606px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.634px;
  ry: 1.222px;
}

</style>
