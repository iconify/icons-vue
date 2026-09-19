<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/ce4bvgyxx.css';
import '../../css/a/a6lp9bcmf.css';
import '../../css/z/zwidvqbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ce4bvgyxx"/><path class="a6lp9bcmf"/><path class="zwidvqbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:signature" /></template>
