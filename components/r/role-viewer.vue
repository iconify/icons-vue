<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0ccxvyfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:role-viewer" /></template>
<style>
.x0ccxvyfh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 8.25q0-1.864 1.318-3.182T9 3.75t3.182 1.318T13.5 8.25t-1.318 3.182T9 12.75t-3.182-1.318T4.5 8.25M1.75 20q0 1.75 1.75 1.75h8.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T13 21v-5q0-.1-.026-.197q-.027-.097-.078-.183q-.05-.087-.122-.157t-.16-.119Q11.094 14.5 9 14.5q-2.97 0-5.037 1.485Q1.75 17.573 1.75 20M18 14.75q-2.555 0-3.929 2.932Q14 17.833 14 18t.071.318Q15.445 21.25 18 21.25t3.929-2.932Q22 18.167 22 18t-.071-.318Q20.555 14.75 18 14.75");
}

</style>
