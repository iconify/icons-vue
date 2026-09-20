<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbqpt1baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qbqpt1baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:quote" /></template>
