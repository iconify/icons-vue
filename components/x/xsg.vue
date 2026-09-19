<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py5dbobda.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="py5dbobda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:xsg" /></template>
