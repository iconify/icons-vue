<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e1t18f8qj.css';
import '../../css/d/dorj-7bxn.css';
import '../../css/c/c_k1iu0hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="e1t18f8qj"/><path clip-rule="evenodd" class="dorj-7bxn"/><path class="c_k1iu0hr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:windsock-bold" /></template>
