<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkiz0wbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="qkiz0wbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:pie-third" /></template>
