<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne2d3dzjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ne2d3dzjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:phice-light" /></template>
