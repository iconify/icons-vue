<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp4h6scln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vp4h6scln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xtz" /></template>
