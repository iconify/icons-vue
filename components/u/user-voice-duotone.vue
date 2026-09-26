<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wqq9tn6nm"/><path class="hpplanbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-duotone" /></template>
<style>
.hpplanbmc {
  d: path("M16.0622 3.5C16.6766 4.5641 17 5.7712 17 7C17 8.2288 16.6766 9.4359 16.0622 10.5M20.247 3C20.7446 4.2749 21 5.6314 21 7C21 8.9309 20.4917 10.8278 19.5263 12.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wqq9tn6nm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 13L11 13C14.866 13 18 16.134 18 20C18 21.1046 17.1046 22 16 22L4 22C2.8954 22 2 21.1046 2 20C2 16.134 5.134 13 9 13ZM14 7C14 9.2091 12.2091 11 10 11C7.7909 11 6 9.2091 6 7C6 4.7909 7.7909 3 10 3C12.2091 3 14 4.7909 14 7Z");
  stroke: none;
}

</style>
