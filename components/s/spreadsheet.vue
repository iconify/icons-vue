<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj9kn0ifj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="jj9kn0ifj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:spreadsheet" /></template>
