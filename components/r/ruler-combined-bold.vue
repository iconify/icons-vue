<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9-lfie1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="m9-lfie1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:ruler-combined-bold" /></template>
