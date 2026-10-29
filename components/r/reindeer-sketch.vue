<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t3de2kb-b.css';
import '../../css/i/i2r2ihbbr.css';
import '../../css/l/l9rauw_7q.css';
import '../../css/m/mh4lfc6ku.css';
import '../../css/i/i_nscfnge.css';
import '../../css/c/cn3_h_bdm.css';
import '../../css/n/nbwrwfbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t3de2kb-b"/><path class="i2r2ihbbr wm-k"/><path class="l9rauw_7q wm-k"/><path class="mh4lfc6ku wm-k"/><path class="i_nscfnge wm-k"/><path class="cn3_h_bdm wm-a"/><circle class="nbwrwfbco wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:reindeer-sketch" /></template>
