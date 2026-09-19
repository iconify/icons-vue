<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv4_thskj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nv4_thskj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:mediafire" /></template>
