<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjp36hbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zjp36hbxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:rotate-counterclockwise-alt" /></template>
