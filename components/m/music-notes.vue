<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e044p0b2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e044p0b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:music-notes" /></template>
