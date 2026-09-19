<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh42s1kew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sh42s1kew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:view-definition" /></template>
