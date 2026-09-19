<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2441nawc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="b2441nawc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:truck-arrow-right" /></template>
