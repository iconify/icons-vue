<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzw2g-byx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uzw2g-byx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:thread" /></template>
