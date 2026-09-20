<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewe08fbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ewe08fbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:photo-14" /></template>
