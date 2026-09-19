<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/le9kem29e.css';
import '../../css/j/j1go70hcn.css';
import '../../css/l/lgr3-yo0q.css';
import '../../css/r/rsqzy8bze.css';
import '../../css/n/n35dlibfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="le9kem29e"/><path class="j1go70hcn"/><circle class="lgr3-yo0q"/><path class="rsqzy8bze"/><path class="n35dlibfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:notification-off-duotone" /></template>
