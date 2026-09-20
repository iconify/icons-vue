<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hienlub7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="hienlub7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:table-top-vertical-rotate-counterclockwise" /></template>
