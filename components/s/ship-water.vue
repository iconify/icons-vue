<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x3swzzy8r.css';
import '../../css/b/b2_3ypb7j.css';
import '../../css/u/uxdt2um9m.css';
import '../../css/i/iw25-fbib.css';
import '../../css/l/ltc6sfbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="x3swzzy8r"/><path clip-rule="evenodd" class="b2_3ypb7j"/><path clip-rule="evenodd" class="uxdt2um9m"/><path clip-rule="evenodd" class="iw25-fbib"/><path class="ltc6sfbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:ship-water" /></template>
