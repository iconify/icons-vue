<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdx8_s66d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="tdx8_s66d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sort" /></template>
