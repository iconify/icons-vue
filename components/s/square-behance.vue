<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azhh47bcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="azhh47bcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:square-behance" /></template>
