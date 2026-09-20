<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvy7v3bvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvy7v3bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tank" /></template>
