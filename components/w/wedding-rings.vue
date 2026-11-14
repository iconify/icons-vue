<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li57dylxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:wedding-rings" /></template>
<style>
.li57dylxg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 6.75q.186 0 .368.009q.368-.541.859-1.032Q12.204 3.75 15 3.75t4.773 1.977T21.75 10.5t-1.977 4.773T15 17.25q-.186 0-.368-.009q-.368.541-.859 1.032Q11.796 20.25 9 20.25t-4.773-1.977T2.25 13.5t1.977-4.773T9 6.75");
}

</style>
