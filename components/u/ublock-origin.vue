<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd4vsgtzi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jd4vsgtzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:ublock-origin" /></template>
