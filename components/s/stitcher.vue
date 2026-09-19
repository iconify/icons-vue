<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5n6mccaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w5n6mccaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:stitcher" /></template>
