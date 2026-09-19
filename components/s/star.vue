<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxy5r9swd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="gxy5r9swd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:star" /></template>
