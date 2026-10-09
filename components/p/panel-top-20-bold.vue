<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkpulpb9y.css';
import '../../css/c/ctld64bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jkpulpb9y"/><path class="ctld64bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-top-20-bold" /></template>
