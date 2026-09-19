<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zohv35dbe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zohv35dbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:mosque" /></template>
