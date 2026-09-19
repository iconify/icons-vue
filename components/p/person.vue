<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wu5mj21vp.css';
import '../../css/v/v8a78x2hg.css';
import '../../css/u/us0h-wb9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wu5mj21vp"/><path class="v8a78x2hg"/><path class="us0h-wb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:person" /></template>
