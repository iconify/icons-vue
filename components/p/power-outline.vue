<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8si1w29y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8si1w29y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:power-outline" /></template>
