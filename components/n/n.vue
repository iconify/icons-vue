<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy43hrxgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="iy43hrxgr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:n" /></template>
