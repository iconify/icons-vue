<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxpg48nlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="xxpg48nlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:three" /></template>
