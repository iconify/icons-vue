<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlxd-7btu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="wlxd-7btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sparkles-bold" /></template>
