<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pap18yb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="pap18yb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:modulo-bold" /></template>
