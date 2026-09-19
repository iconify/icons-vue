<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sygjhfptx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="sygjhfptx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:trello" /></template>
