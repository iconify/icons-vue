<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y71q3cb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y71q3cb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:postcard-bold" /></template>
