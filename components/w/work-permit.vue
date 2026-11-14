<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-j76lb0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:work-permit" /></template>
<style>
.j-j76lb0w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q2.75 0 2.75 2.75v2q0 .719-.188 1.25h2.688q2 0 2 2t-2 2H6.75q-2 0-2-2t2-2h2.688Q9.25 7.219 9.25 6.5v-2q0-2.75 2.75-2.75m-4.5 16q0-1.864 1.318-3.182T12 13.25t3.182 1.318T16.5 17.75t-1.318 3.182T12 22.25h-.002q-1.863-.001-3.18-1.318T7.5 17.75");
}

</style>
