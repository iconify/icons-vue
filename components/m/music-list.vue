<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfg0owgcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="hfg0owgcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:music-list" /></template>
