<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dixj3-b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":472,"height":384};
const content = `<path class="dixj3-b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:ruler" /></template>
