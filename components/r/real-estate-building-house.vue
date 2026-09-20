<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi6pzub_r.css';
import '../../css/s/sqglgeskz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oi6pzub_r"/><path class="sqglgeskz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:real-estate-building-house" /></template>
