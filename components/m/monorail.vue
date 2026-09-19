<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz1map5pe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xz1map5pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:monorail" /></template>
