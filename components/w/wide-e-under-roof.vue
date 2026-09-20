<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8gosiblu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f8gosiblu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:wide-e-under-roof" /></template>
