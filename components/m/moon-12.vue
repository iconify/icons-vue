<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm_0b6bit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="wm_0b6bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:moon-12" /></template>
