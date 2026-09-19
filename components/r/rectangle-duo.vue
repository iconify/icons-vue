<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo7iwkb_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<rect class="wo7iwkb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:rectangle-duo" /></template>
