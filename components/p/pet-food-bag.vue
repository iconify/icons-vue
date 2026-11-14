<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da874ob3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pet-food-bag" /></template>
<style>
.da874ob3a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 2.75H6.25q-2.5 0-2.5 2.5q0 1.554.966 2.142L3.752 19.44l-.002.06q0 2.25 2.25 2.25h12q2.25 0 2.25-2.25l-.002-.06l-.964-12.048q.966-.588.966-2.142q0-1.036-.732-1.768T17.75 2.75m.058 5l.942 11.777q-.014.723-.75.723H6q-.736 0-.75-.723L6.192 7.75zm-11.558 5q0 .775.301 1.25q-.301.475-.301 1.25q0 2 2 2q1.581 0 1.912-1.25h3.676q.331 1.25 1.912 1.25q2 0 2-2q0-.775-.301-1.25q.301-.475.301-1.25q0-2-2-2q-1.581 0-1.912 1.25h-3.676q-.331-1.25-1.912-1.25q-2 0-2 2");
}

</style>
