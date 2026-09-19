<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j9zzo3bwq.css';
import '../../css/q/qbvum3bcn.css';
import '../../css/e/e_fmn1lsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j9zzo3bwq"/><path class="qbvum3bcn"/><path class="e_fmn1lsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stop-sign-duo" /></template>
