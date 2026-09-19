<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbfi2qb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jbfi2qb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:right-panel-open-filled" /></template>
