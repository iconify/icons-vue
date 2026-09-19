<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9xi539mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o9xi539mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:prev" /></template>
