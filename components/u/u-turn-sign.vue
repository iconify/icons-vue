<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/g/gzha3o9cv.css';
import '../../css/a/anocjeqrh.css';
import '../../css/m/mewrxib2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="gzha3o9cv"/><path class="anocjeqrh"/><path class="mewrxib2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:u-turn-sign" /></template>
