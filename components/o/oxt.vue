<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d65b-8b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d65b-8b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:oxt" /></template>
