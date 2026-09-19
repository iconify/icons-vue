<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf11m8dlt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bf11m8dlt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:srn" /></template>
