<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9krj_bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="k9krj_bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:seek-step" /></template>
