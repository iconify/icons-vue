<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srljlebzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="srljlebzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:theatre-14" /></template>
