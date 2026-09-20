<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fl7p-6xcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fl7p-6xcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:part-of-circle-1" /></template>
