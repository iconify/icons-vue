<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lngcvmxva.css';
import '../../css/c/cl68f3slr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lngcvmxva"/><path class="cl68f3slr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:pink-heart" /></template>
