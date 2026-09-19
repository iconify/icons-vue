<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oil4e9epc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<rect class="oil4e9epc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:stop" /></template>
