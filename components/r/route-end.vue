<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx-z35byx.css';
import '../../css/r/rug5b1b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="zx-z35byx"/><path class="rug5b1b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:route-end" /></template>
