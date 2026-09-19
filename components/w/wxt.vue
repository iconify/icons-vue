<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpm4eacfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wpm4eacfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:wxt" /></template>
