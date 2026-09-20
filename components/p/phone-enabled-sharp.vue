<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js0eafbcm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-enabled-sharp" /></template>
<style>
.js0eafbcm {
  fill: currentColor;
  d: path("M4.8 20H4v-4.413l3.75-.756l2.612 2.708q1.288-.71 2.295-1.44t1.808-1.57q.794-.788 1.527-1.77q.733-.98 1.417-2.167l-2.695-2.51L15.562 4H20v.8q0 2.67-1.254 5.402t-3.523 5.021q-2.289 2.289-5.005 3.533T4.8 20");
}

</style>
