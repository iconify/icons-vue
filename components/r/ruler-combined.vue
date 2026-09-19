<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e296fw0ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="e296fw0ge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ruler-combined" /></template>
