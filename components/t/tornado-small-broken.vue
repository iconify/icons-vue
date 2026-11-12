<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mevf1wekm"/><path class="ik-b2z0to"/><path class="l8ziygp-z"/><path class="ah9y98gxq"/><path class="ln19sqozd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tornado-small-broken" /></template>
<style>
.ah9y98gxq {
  d: path("M13 19C11.6484 19 10.6575 18.8786 10 18.7554M16 18.5C15.6982 18.6031 15.3714 18.7045 15 18.7887");
}

.ik-b2z0to {
  d: path("M20 10C20 10 17.2089 11 11.7241 11C6.23938 11 4 10 4 10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8ziygp-z {
  d: path("M16 16C16 16 14.7424 16.5 12 16.5C9.25762 16.5 8 16 8 16");
}

.ln19sqozd {
  d: path("M18 13C18 13 17.4848 14 12 14M7.8918 13.721C6.21904 13.4251 6 13 6 13");
}

.mevf1wekm {
  d: path("M12 8C16.9706 8 21 7.32843 21 6.5C21 5.97993 19.412 5.52168 17 5.25259M12 5C7.02944 5 3 5.67157 3 6.5C3 7.08895 5.03656 7.59863 8 7.84408");
}

</style>
