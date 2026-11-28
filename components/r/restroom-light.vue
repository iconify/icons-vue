<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9xf69qzd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="o9xf69qzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:restroom-light" /></template>
