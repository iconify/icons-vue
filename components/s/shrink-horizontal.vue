<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epha_l8gi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epha_l8gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:shrink-horizontal" /></template>
