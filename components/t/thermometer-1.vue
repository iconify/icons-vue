<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2y3f5bzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1792};
const content = `<path class="k2y3f5bzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:thermometer-1" /></template>
