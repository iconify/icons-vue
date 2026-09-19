<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0trscbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="y0trscbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:store-break" /></template>
