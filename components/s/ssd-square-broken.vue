<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jk7q_7_zl"/><path class="naf-65baz"/><path class="upt2i_ovk"/><path class="cwsij8mcs"/><path class="pjz_jnbra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ssd-square-broken" /></template>
<style>
.cwsij8mcs {
  d: path("M11.5 17V18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jk7q_7_zl {
  d: path("M19 17V18");
}

.naf-65baz {
  d: path("M16.5 17V18");
}

.pjz_jnbra {
  d: path("M21.8515 14.9557L21.8515 14.9556M21.8515 14.9556L20.4258 10.0367M21.8515 14.9556C22 15.4614 22 16.1625 22 17.2941C22 18.7812 22 19.5247 21.6629 20.0589C21.517 20.2901 21.3295 20.4886 21.1111 20.6431C20.6067 21 19.9045 21 18.5 21H12M21.8515 14.9556C21.8048 14.7967 21.7435 14.6571 21.6629 14.5294C21.517 14.2982 21.3295 14.0996 21.1111 13.9451C20.6067 13.5882 19.9045 13.5882 18.5 13.5882H5.5C4.09554 13.5882 3.39331 13.5882 2.88886 13.9451C2.67048 14.0996 2.48298 14.2982 2.33706 14.5294C2 15.0635 2 15.807 2 17.2941C2 18.7812 2 19.5247 2.33706 20.0589C2.48298 20.2901 2.67048 20.4886 2.88886 20.6431C3.39331 21 4.09554 21 5.5 21H8M2.14849 14.9557L5 5.11765C5.5 3.52941 6.39543 3 7.5 3H16.5C17.6046 3 18.5 3.52941 19 5.11765L19.3564 6.34741");
}

.upt2i_ovk {
  d: path("M14 17V18");
}

</style>
