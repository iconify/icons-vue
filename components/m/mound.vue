<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lr0zcubfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="lr0zcubfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:mound" /></template>
