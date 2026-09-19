<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvis7qbvb.css';
import '../../css/s/s9ppw9blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uvis7qbvb"/><circle class="s9ppw9blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:medication-reminder" /></template>
