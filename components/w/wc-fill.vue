<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r8qftrbnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r8qftrbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:wc-fill" /></template>
