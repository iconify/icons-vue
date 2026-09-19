<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ykhb4xi8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ykhb4xi8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:ringed-planet" /></template>
