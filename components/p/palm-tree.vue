<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uytvyyfuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="uytvyyfuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:palm-tree" /></template>
