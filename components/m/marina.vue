<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ry2ixoy8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="ry2ixoy8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="map:marina" /></template>
