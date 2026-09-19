<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ayznvdnzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ayznvdnzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:strikethrough" /></template>
