<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qp_3d5bfd.css';
import '../../css/d/djut3k-ln.css';
import '../../css/k/kt7wgubkd.css';
import '../../css/g/gmw4v2fmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qp_3d5bfd"/><path class="djut3k-ln wm-a"/><path class="kt7wgubkd wm-k"/><path class="gmw4v2fmm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-function-sketch" /></template>
