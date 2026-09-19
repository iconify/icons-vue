<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx7r32bwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx7r32bwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-arrow-round-back" /></template>
