<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szrmdj49d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="szrmdj49d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:reading-glasses" /></template>
