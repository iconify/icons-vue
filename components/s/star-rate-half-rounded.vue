<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjuyjbcyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:star-rate-half-rounded" /></template>
<style>
.tjuyjbcyi {
  fill: currentColor;
  d: path("M12 7.9v5.9l2.4 1.85l-.9-3.05l2.25-1.6h-2.8zm0 7.17l-3.027 2.305q-.16.11-.321.097t-.296-.091t-.205-.235t-.003-.333l1.156-3.798l-2.875-2.075q-.166-.104-.212-.265t.016-.321t.186-.257t.302-.097h3.61l1.18-3.877q.068-.177.196-.278q.127-.1.293-.1t.293.1q.128.101.196.278L13.669 10h3.61q.177 0 .302.097t.186.257t.016.321q-.047.162-.212.266l-2.875 2.074l1.156 3.798q.067.177-.003.333t-.205.235t-.296.091t-.321-.097z");
}

</style>
