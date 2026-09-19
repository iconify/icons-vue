<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq83v1bct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tq83v1bct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:warning-diamond-fill" /></template>
