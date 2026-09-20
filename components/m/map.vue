<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx82w-bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:map" /></template>
<style>
.zx82w-bdm {
  fill: currentColor;
  d: path("m15 19.923l-6-2.1l-3.958 1.53q-.384.143-.713-.083T4 18.634V6.404q0-.268.13-.489t.378-.307L9 4.077l6 2.1l3.958-1.53q.384-.143.713.054t.329.588v12.384q0 .287-.159.498q-.158.212-.426.298zm-.5-1.22v-11.7l-5-1.745v11.7z");
}

</style>
