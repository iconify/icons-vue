<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atfdt7ybg.css';
import '../../css/i/ijiizvbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="atfdt7ybg"/><path class="ijiizvbfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:toggle-right-20-bold" /></template>
