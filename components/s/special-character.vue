<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ris3ovb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ris3ovb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:special-character" /></template>
