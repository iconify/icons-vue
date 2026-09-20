<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue86ivb3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="ue86ivb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-night-701" /></template>
