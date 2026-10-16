<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/erzf03bmv.css';
import '../../css/h/hll1-sbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="hll1-sbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:miniflux" /></template>
