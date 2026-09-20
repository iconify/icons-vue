<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kln7xeb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="kln7xeb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:yahoo-13" /></template>
