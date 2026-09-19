<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkv818cfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tkv818cfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:view-expand-bold" /></template>
