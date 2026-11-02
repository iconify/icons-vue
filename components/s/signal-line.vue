<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/is1ae6bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is1ae6bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:signal-line" /></template>
