<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srfh7msce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1536};
const content = `<path class="srfh7msce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:strikethrough" /></template>
