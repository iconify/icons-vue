<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fq5-1l2ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fq5-1l2ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:tablet" /></template>
