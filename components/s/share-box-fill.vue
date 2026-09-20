<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6fy3d2pj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6fy3d2pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:share-box-fill" /></template>
