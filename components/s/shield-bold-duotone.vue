<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m51pkuzhy"/><path class="rh_uhdcwo"/><g class="xtpeb-edw"><path class="ho1hk4giy"/><path class="fu9tnywzi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-bold-duotone" /></template>
<style>
.fu9tnywzi {
  d: path("M12 8L3 11V10.417C3 7.21941 3.00041 5.6199 3.37793 5.08203C3.75595 4.54434 5.25909 4.02979 8.26465 3.00098L8.83789 2.80469C10.405 2.26825 11.1886 2 12 2V8Z");
}

.ho1hk4giy {
  d: path("M21 11V11.9912C21 17.6292 16.7612 20.3655 14.1016 21.5273C13.3801 21.8425 13.0193 22 12 22V8L21 11Z");
}

.m51pkuzhy {
  fill: currentColor;
  d: path("M12 22C10.9807 22 10.6199 21.8425 9.89844 21.5273C7.23883 20.3655 3 17.6292 3 11.9912V11L12 8V22Z");
}

.rh_uhdcwo {
  fill: currentColor;
  d: path("M12 2C12.8114 2 13.595 2.26825 15.1621 2.80469L15.7354 3.00098C18.7409 4.02979 20.244 4.54434 20.6221 5.08203C20.9996 5.6199 21 7.21941 21 10.417V11L12 8V2Z");
}

.xtpeb-edw {
  fill: currentColor;
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
