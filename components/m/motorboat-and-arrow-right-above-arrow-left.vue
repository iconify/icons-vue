<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd8e2usik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wd8e2usik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:motorboat-and-arrow-right-above-arrow-left" /></template>
