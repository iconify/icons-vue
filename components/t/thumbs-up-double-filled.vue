<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w80hshjhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w80hshjhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:thumbs-up-double-filled" /></template>
