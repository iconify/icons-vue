<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h8aqxbbrl.css';
import '../../css/q/q-w374b1g.css';
import '../../css/j/juykxi29h.css';
import '../../css/v/vxtp-z-ls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h8aqxbbrl"/><path class="q-w374b1g"/><path clip-rule="evenodd" class="juykxi29h"/><rect class="vxtp-z-ls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:temperature" /></template>
