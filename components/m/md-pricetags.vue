<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt52jcc3i.css';
import '../../css/n/ns2y_7_hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rt52jcc3i"/><path class="ns2y_7_hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-pricetags" /></template>
