<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy6q70buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zy6q70buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-cane" /></template>
