<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sj241obqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sj241obqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:nkn" /></template>
