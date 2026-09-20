<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctpwnv3dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ctpwnv3dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:move-last-rtl" /></template>
