<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2yfbmbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2yfbmbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:recent-changes-rtl" /></template>
