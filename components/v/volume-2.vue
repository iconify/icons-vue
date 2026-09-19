<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4wc7m-ir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="x4wc7m-ir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:volume-2" /></template>
