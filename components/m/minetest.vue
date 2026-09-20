<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="liy344bqy"/><path class="mhzedi9nh"/><path class="fg27xkl4z"/><path class="nc_ulcc0c"/><path class="o2ws0ebwb"/><path class="ay13l0b5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minetest" /></template>
<style>
.ay13l0b5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.744 15.575l6.65 3.84l6.006-3.468V8.418l-6.005-3.467l-6.65 3.839Zm27.12 6.618l1.451.837l1.261-.728V14.72l-1.26-.728l-1.452.97ZM43 25.499l-3.616 2.088v.904l-1.808 1.043v1.808l-1.808 1.044v3.616L43 31.827Zm-25.312 3.049v1.808");
}

.fg27xkl4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.688 39.396l-9.556-5.518l3.137-1.742l2.803 1.556m20.792-16.598L32.2 15.221l-6.056 3.654l4.201 2.515v1.81l5.96 3.447l3.136-1.808L43 22.787l-5.424-3.815m-5.377-3.75l-.047-1.827");
}

.liy344bqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43 31.827zL24.016 43.049L5 32.07V21.223");
}

.mhzedi9nh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.552 29.275L7.744 28.23v5.424l9.782 5.647v-1.808l-1.566-.904v-1.808l-1.888-1.09v-3.616l-4.52-2.61Z");
}

.nc_ulcc0c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.245 17.596L5 21.223l12.688 7.325l12.656-7.157l-5.78-3.465l7.588-4.53l-6.797-3.925l-4.712 2.914M30.344 23.2l-12.656 7.156v1.808l1.404.81v1.808l4.924 2.843l10.848-6.393v-1.94l1.512-.872l-.071-1.773");
}

.o2ws0ebwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.803 18.495l.026 3.821l1.566.714l1.565-.714V20.51l-.023-1.993l-1.542.899");
}

</style>
