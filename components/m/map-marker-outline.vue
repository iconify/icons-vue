<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6ya0ub4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l6ya0ub4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:map-marker-outline" /></template>
