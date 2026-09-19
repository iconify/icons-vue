<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv9mw16ld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":480};
const content = `<path class="wv9mw16ld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-ring" /></template>
