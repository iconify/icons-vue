<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c01ffwbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c01ffwbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:record-vinyl" /></template>
