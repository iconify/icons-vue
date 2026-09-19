<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/synbksvac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="synbksvac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view-mode-1" /></template>
