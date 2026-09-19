<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nof7r7bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nof7r7bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:parameter-action" /></template>
