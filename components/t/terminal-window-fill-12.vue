<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-6icjxui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t-6icjxui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:terminal-window-fill-12" /></template>
