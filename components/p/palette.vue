<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duv8mepcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="duv8mepcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:palette" /></template>
