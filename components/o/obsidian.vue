<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sei62mbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:obsidian" /></template>
<style>
.sei62mbzp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.284 11.844l1.457-9.227q.035-.22-.056-.423q.297.131.587.363l5.922 4.737q1.162.931.76 2.364l-2.821 10.078q-.146.522-.481.894l-.012-.021zm4.054 9.511q-.493.085-1.011-.069L4.754 18.154q-.906-.269-1.349-1.104t-.156-1.735L6.11 6.323q.263-.826 1.011-1.262l4.612-2.69q.321-.187.634-.273q-.084.131-.108.285l-1.5 9.5q-.021.132.005.263t.096.245z");
}

</style>
