<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybhhwn4il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="ybhhwn4il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:wikipedia-w" /></template>
