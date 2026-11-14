<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8yupf3un"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-drop" /></template>
<style>
.w8yupf3un {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 9.75q0 5.592 7.759 12.317q.051.044.108.078q.058.034.121.058q.063.023.129.035t.133.012t.133-.012t.129-.035q.063-.024.121-.058t.108-.078Q20.25 15.342 20.25 9.75q0-3.417-2.416-5.834T12 1.5T6.166 3.916Q3.75 6.333 3.75 9.75m4.75 0q0-3.5 3.5-3.5t3.5 3.5t-3.5 3.5t-3.5-3.5");
}

</style>
