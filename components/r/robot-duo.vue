<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rdgd1mbja.css';
import '../../css/m/m39p55xqg.css';
import '../../css/e/e5k6yebuc.css';
import '../../css/g/gexw8i-wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="rdgd1mbja"/><path class="m39p55xqg"/><path class="e5k6yebuc"/><path class="gexw8i-wt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:robot-duo" /></template>
