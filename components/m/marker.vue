<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odpp73b1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="odpp73b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:marker" /></template>
