<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/k/kgugpibha.css';
import '../../css/o/os5b4vbrt.css';
import '../../css/s/sj1g9qbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="kgugpibha"/><path class="os5b4vbrt"/><path class="sj1g9qbqm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:satellite" /></template>
