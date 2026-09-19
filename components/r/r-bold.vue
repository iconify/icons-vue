<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq25edcdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="eq25edcdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:r-bold" /></template>
