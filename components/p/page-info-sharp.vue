<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-77emaqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-info-sharp" /></template>
<style>
.t-77emaqe {
  fill: currentColor;
  d: path("M15.472 18.201q-.856-.857-.856-2.085q0-1.23.856-2.086q.857-.857 2.086-.857t2.085.857t.857 2.086t-.857 2.085t-2.085.857q-1.23 0-2.086-.857M5 16.616v-1h7.23v1zM4.357 9.97Q3.5 9.113 3.5 7.884T4.357 5.8t2.085-.857q1.23 0 2.086.857q.857.857.857 2.085q0 1.23-.857 2.086q-.857.857-2.086.857T4.357 9.97m7.412-1.586v-1H19v1z");
}

</style>
