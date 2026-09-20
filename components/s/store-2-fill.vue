<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7-p5eb0s.css';
import '../../css/e/e2w581g2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s7-p5eb0s"/><path class="e2w581g2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:store-2-fill" /></template>
