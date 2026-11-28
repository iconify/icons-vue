<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztrv4pb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ztrv4pb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:text-wrap-light" /></template>
