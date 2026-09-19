<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o-2ja8zjz.css';
import '../../css/a/aeb7ubc3o.css';
import '../../css/w/w-97wcbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="o-2ja8zjz"/><path class="aeb7ubc3o"/><path class="w-97wcbeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:volume-3" /></template>
