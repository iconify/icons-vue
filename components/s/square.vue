<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/se2hntbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="se2hntbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:square" /></template>
