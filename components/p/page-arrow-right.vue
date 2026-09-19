<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxz0sv_bt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="uxz0sv_bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:page-arrow-right" /></template>
