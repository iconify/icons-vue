<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt6acgbrk.css';
import '../../css/t/tk0tl-b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yt6acgbrk"/><path class="tk0tl-b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:newspaper-16-solid" /></template>
