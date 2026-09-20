<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmt2g6bzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vmt2g6bzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:pancreas" /></template>
