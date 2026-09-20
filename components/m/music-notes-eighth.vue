<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh1ch4dcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zh1ch4dcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:music-notes-eighth" /></template>
