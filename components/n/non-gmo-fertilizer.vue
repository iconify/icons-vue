<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0nb7cc6b.css';
import '../../css/o/o3ain3blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d0nb7cc6b"/><path class="o3ain3blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:non-gmo-fertilizer" /></template>
