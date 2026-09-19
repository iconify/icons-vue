<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n772abchy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n772abchy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:mobility-services" /></template>
