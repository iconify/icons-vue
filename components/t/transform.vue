<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz2b7dbmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":480};
const content = `<path class="jz2b7dbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:transform" /></template>
