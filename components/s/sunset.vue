<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfw6i0twr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sfw6i0twr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sunset" /></template>
