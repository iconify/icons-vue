<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gys_s0bwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gys_s0bwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:map-pin-outline-with-dot" /></template>
