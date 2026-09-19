<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uceuolr2w.css';
import '../../css/r/rja0tvb5w.css';
import '../../css/b/b2diuqr2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="uceuolr2w"/><path class="rja0tvb5w"/><path class="b2diuqr2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:pennant-1-bold" /></template>
