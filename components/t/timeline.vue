<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6c-53fwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u6c-53fwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:timeline" /></template>
