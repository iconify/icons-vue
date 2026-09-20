<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2om1_1xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i2om1_1xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:view-compact" /></template>
