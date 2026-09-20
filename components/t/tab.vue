<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdii07f6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":16};
const content = `<path class="qdii07f6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:tab" /></template>
