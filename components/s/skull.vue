<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/i/ilwnqgbrm.css';
import '../../css/a/a2_bt0bia.css';
import '../../css/l/l5gr8x1yh.css';
import '../../css/c/caxq9wb2w.css';
import '../../css/c/cvucmfbbm.css';
import '../../css/h/hp9sv0bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><linearGradient id="SVGvkVIAbPV" x1="0" x2="0" y1="0" y2="1"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="ilwnqgbrm"/></linearGradient></defs><g transform="matrix(2.4 0 0 2.4 16 16)"><path fill="url(#SVGvkVIAbPV)" class="a2_bt0bia"/><ellipse class="l5gr8x1yh"/><ellipse class="caxq9wb2w"/><path class="cvucmfbbm"/><path class="hp9sv0bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="xero-emoji:skull" /></template>
