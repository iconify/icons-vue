<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dc7yqi9bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="dc7yqi9bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:minus" /></template>
