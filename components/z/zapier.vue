<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipu15wbwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ipu15wbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:zapier" /></template>
