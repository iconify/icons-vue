<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/ds2fwszxt.css';
import '../../css/e/ey2gg78wq.css';
import '../../css/o/oaw0c1bnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ds2fwszxt"/><path class="ey2gg78wq"/><path class="oaw0c1bnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tools-bold" /></template>
