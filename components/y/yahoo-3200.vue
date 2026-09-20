<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4oj3_btn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="k4oj3_btn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:yahoo-3200" /></template>
