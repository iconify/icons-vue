<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0inoxbwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w0inoxbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:strikethrough-y" /></template>
