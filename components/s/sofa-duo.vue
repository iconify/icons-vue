<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k89cfmtkm.css';
import '../../css/j/jvbzfrb1r.css';
import '../../css/d/dsgw4pnpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k89cfmtkm"/><path class="jvbzfrb1r"/><path class="dsgw4pnpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sofa-duo" /></template>
