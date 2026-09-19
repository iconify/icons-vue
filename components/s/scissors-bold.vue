<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/u-je94bsz.css';
import '../../css/o/oz6v0cqzz.css';
import '../../css/x/x01h8kb6t.css';
import '../../css/u/u1pyc2bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="u-je94bsz"/><path class="oz6v0cqzz"/><path clip-rule="evenodd" class="x01h8kb6t"/><path class="u1pyc2bti"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:scissors-bold" /></template>
