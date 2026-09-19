<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px97jfvaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="px97jfvaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:pli" /></template>
