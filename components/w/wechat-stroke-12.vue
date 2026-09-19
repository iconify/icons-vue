<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p2e80kbeg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p2e80kbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:wechat-stroke-12" /></template>
