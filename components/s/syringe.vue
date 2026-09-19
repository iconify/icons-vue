<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/c5qci8b2s.css';
import '../../css/c/cbuolj-4j.css';
import '../../css/r/r9a985b0x.css';
import '../../css/b/b888d11zq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="bi12bsetm"><path class="c5qci8b2s"/><path class="cbuolj-4j"/><path class="r9a985b0x"/><path class="b888d11zq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:syringe" /></template>
