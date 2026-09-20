<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-1yv-bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-1yv-bzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openfga-dark" /></template>
