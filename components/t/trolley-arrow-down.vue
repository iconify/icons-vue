<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/l/latz-6nki.css';
import '../../css/b/bcv2mrb4w.css';
import '../../css/c/c-j37uq4f.css';
import '../../css/h/hadrnbvhd.css';
import '../../css/w/wekugib4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<g class="bi12bsetm"><path class="latz-6nki"/><path class="bcv2mrb4w"/><path class="c-j37uq4f"/><path class="hadrnbvhd"/><path class="wekugib4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:trolley-arrow-down" /></template>
