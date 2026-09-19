<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfjo-w2pn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="dfjo-w2pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:star-half" /></template>
