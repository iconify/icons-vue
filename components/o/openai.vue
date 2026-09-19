<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2mbb37pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e2mbb37pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:openai" /></template>
