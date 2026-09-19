<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4fd6hbib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v4fd6hbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:sub-volume" /></template>
