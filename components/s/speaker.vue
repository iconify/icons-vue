<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/d/d4jw9nboq.css';
import '../../css/h/hh22srh1i.css';
import '../../css/p/p94o0ic_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="d4jw9nboq"/><path class="hh22srh1i"/><path class="p94o0ic_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:speaker" /></template>
