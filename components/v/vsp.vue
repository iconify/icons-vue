<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vn6g0qbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vsp" /></template>
<style>
.vn6g0qbjs {
  fill: var(--svg-color--4138ab, #4138ab);
  d: path("M9.968 3.871H3l1.164 3.484H7.29l4.419 12.774h3.484L21 3.871h-3.774l-3.774 11.032z");
}

</style>
