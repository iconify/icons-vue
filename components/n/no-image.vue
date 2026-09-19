<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nd0bibcim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nd0bibcim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:no-image" /></template>
