<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg23gwpnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="cg23gwpnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:triangle-duo" /></template>
