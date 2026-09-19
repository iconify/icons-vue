<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/n/nndam4mwm.css';
import '../../css/i/ifaxg67dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="nndam4mwm"/><path class="ifaxg67dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:union" /></template>
