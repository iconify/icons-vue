<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh5f3c7jr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<path class="zh5f3c7jr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:percentage" /></template>
