<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6bc1hbel.css';
import '../../css/d/d8vaue9uw.css';
import '../../css/d/dtcgrhbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6bc1hbel"/><path class="d8vaue9uw"/><path class="dtcgrhbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:watsonx-data" /></template>
