<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nn5mlkxwd.css';
import '../../css/j/jt9uwcc7h.css';
import '../../css/o/oolf1cc2n.css';
import '../../css/r/r95ie0b3v.css';
import '../../css/m/m_q0ucbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="nn5mlkxwd"/><path class="jt9uwcc7h"/><path class="oolf1cc2n"/><path class="r95ie0b3v"/><path class="m_q0ucbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:sunrise-1" /></template>
