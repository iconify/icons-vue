<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf10fbbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="zf10fbbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:pencil-square" /></template>
