<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g81rdnxxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="g81rdnxxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:times-outline" /></template>
