<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xemra3bhx.css';
import '../../css/v/vfn6b26gs.css';
import '../../css/n/njdlg4bft.css';
import '../../css/v/vmc9b_bpg.css';
import '../../css/s/syv5jmb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="xemra3bhx"/><path class="vfn6b26gs"/><path clip-rule="evenodd" class="njdlg4bft"/><path class="vmc9b_bpg"/><path clip-rule="evenodd" class="syv5jmb2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:pharmacy-1" /></template>
