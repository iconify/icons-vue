<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/cbay_mbbl.css';
import '../../css/k/kb4o8e-ai.css';
import '../../css/k/kzxllvf1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="cbay_mbbl"/><path class="kb4o8e-ai"/><path class="kzxllvf1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:polaroid" /></template>
