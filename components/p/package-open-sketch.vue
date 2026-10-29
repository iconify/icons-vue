<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l3w9o904c.css';
import '../../css/n/nw025lbnr.css';
import '../../css/d/dgmk__b2x.css';
import '../../css/d/d1v43fshw.css';
import '../../css/s/sqb3ibhos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l3w9o904c"/><path class="nw025lbnr wm-k"/><path class="dgmk__b2x wm-a"/><path class="d1v43fshw wm-k"/><path class="sqb3ibhos wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:package-open-sketch" /></template>
