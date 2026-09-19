<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehrz3ubhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ehrz3ubhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:session-border-control" /></template>
