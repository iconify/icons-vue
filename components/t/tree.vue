<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/savjuf6vg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="savjuf6vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tree" /></template>
