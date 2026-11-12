<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="rst3o_bug"/><path class="j-r-_cchv"/><path class="viplyobnz"/><path class="jc09h587p"/><path class="obcs1cbgf"/><path class="lbj2v8dkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:microphone-off-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-r-_cchv {
  d: path("M16.9995 10.4561V11.0001C16.9995 13.7615 14.7609 16.0001 11.9995 16.0001C11.8075 16.0001 11.6175 15.9891 11.4785 15.9771");
}

.jc09h587p {
  d: path("M8.98633 18.413C9.91633 18.792 10.9333 19 12.0003 19M15.8763 18C18.3353 16.635 20.0003 14.012 20.0003 11V10");
}

.lbj2v8dkg {
  d: path("M13 8H16");
}

.obcs1cbgf {
  d: path("M12 19V22");
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.rst3o_bug {
  d: path("M9 15C7.785 14.088 7 12.636 7 11V8C7 5.2386 9.2386 3 12 3C14.448 3 16.486 4.76 16.916 7.084");
}

.viplyobnz {
  d: path("M4 10V11C4 13.464 5.114 15.667 6.865 17.135");
}

</style>
