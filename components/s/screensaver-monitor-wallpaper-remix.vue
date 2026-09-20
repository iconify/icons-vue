<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg2y4rbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cg2y4rbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:screensaver-monitor-wallpaper-remix" /></template>
