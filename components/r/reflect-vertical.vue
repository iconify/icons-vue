<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbpd_gbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bbpd_gbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reflect-vertical" /></template>
