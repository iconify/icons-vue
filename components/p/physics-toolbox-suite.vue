<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h1em7dd_l"/><circle class="koirx5wkr"/><path class="h8zeemfru"/><circle class="ujz-c5b2f"/><path class="h6tc6ckqv"/><circle class="uae_dzb7a"/><path class="btqaa2bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:physics-toolbox-suite" /></template>
<style>
.btqaa2bjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.911 16.966l4.474 1.198m-5.092-4.86l5.022 1.346a.874.874 0 0 0 1.07-.618l.068-.253m-5.005.784l.475-1.772m5.304-4.9a1.75 1.75 0 0 1 .46 1.695h0a1.75 1.75 0 0 1-2.141 1.236l-1.097-.294a1.75 1.75 0 0 1-1.236-2.14h0a1.75 1.75 0 0 1 2.14-1.236l.549.147l-.905 3.376");
}

.h1em7dd_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.58 37.62a31.9 31.9 0 0 1-13.568 2.515M10.887 36.28a32 32 0 0 1-4.396-2.885");
}

.h6tc6ckqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.045 31.163c.65-.27.99-.735 1.183-1.457l.268-1a1.744 1.744 0 0 0-1.233-2.135l-.008-.002a1.744 1.744 0 0 0-2.135 1.233l-.296 1.103a1.746 1.746 0 0 1-2.138 1.234h0a1.75 1.75 0 0 1-1.237-2.143l.266-.994c.194-.722.534-1.188 1.184-1.457m2.371-2.241l2.785.746c.932.25 1.89-.303 2.14-1.236h0a1.75 1.75 0 0 0-1.235-2.14l-2.786-.746");
}

.h8zeemfru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.965 30.981L26.751 5.5m6.082 6.689l1.357-5.066l1.595 2.762l-1.595-2.762l-2.76 1.594l2.76-1.594m-3.916 14.256l1.96-7.313l1.594 2.762l-1.595-2.762l-2.76 1.594l2.76-1.594m-5.162 19.256l2.708-10.105l1.595 2.762l-1.595-2.762l-2.76 1.594l2.76-1.594m4.281 7.146l1.14 2.67l2.498-1.746l3.811-13.628l-1.068-2.599l-2.594 1.55z");
}

.koirx5wkr {
  cx: 18.297px;
  cy: 36.675px;
  r: 5.825px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uae_dzb7a {
  cx: 10.844px;
  cy: 16.412px;
  r: 0.75px;
  fill: currentColor;
}

.ujz-c5b2f {
  cx: 37.757px;
  cy: 23.98px;
  r: 0.75px;
  fill: currentColor;
}

</style>
