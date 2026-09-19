<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr-yqlb9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lr-yqlb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rotate-clockwise-alt-filled" /></template>
