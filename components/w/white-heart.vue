<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfxqu7bxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dfxqu7bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-heart" /></template>
