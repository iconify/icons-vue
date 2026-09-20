<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":257};
const content = `<path class="xpx04d8vd"/><path class="ap589ibze"/><path class="vzwjf192t"/><path class="s0i9_ptuy"/><path class="pdkhzjb7e"/><path class="no7iteb0s"/><path class="ulhnow6fv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:terser-icon" /></template>
<style>
.ap589ibze {
  fill: var(--svg-color--ffc843, #ffc843);
  d: path("m128.27 160.204l34.098 27.06v69.277H94.173v-69.277zm34.098-90.927V0H94.173v69.277l34.098 27.407z");
}

.no7iteb0s {
  fill: var(--svg-color--008c3c, #008c3c);
  d: path("M162.368 147.755v39.51L128.27 167.78l13.699-15zM128.27 88.76L94.173 69.277v39.51l22.371-3.68z");
}

.pdkhzjb7e {
  fill: var(--svg-color--ff350f, #ff350f);
  d: path("m128.27 88.761l34.098-19.484v39.51l-22.499-3.948zm-34.097 58.994v39.51l34.098-19.485l-11.943-18.496z");
}

.s0i9_ptuy {
  fill: var(--svg-color--002f32, #002f32);
  d: path("m162.368 108.786l33.556 19.485l-33.556 19.484l-6.6-19.484zm-68.195 0l-34.097 19.485l34.097 19.484l7.58-19.484z");
}

.ulhnow6fv {
  fill: var(--svg-color--00250d, #00250d);
  d: path("m128.271 88.761l-34.098 20.025v38.969l34.098 20.025l34.097-20.025v-38.969z");
}

.vzwjf192t {
  fill: var(--svg-color--ff4338, #ff4338);
  d: path("m157.359 113.344l5.009-44.067l59.535-34.639L256 93.632l-60.076 34.639zM60.076 128.27L0 162.909l34.097 58.994l60.076-34.639l9.936-42.419z");
}

.xpx04d8vd {
  fill: var(--svg-color--00b3e3, #00b3e3);
  d: path("m99.405 111.85l-39.329 16.42L0 93.633l34.638-58.994l59.535 34.639zm57.954 33.075l5.009 42.34l59.535 34.638L256 162.909l-60.076-34.638z");
}

</style>
