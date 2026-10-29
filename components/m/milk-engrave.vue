<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uic09-b6z.css';
import '../../css/g/gdvhu285q.css';
import '../../css/l/l1pdc8-1w.css';
import '../../css/n/nhm3kcoqx.css';
import '../../css/o/ovzt3sbip.css';
import '../../css/w/w87_sfbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uic09-b6z wm-k"/><path class="gdvhu285q wm-a"/><path class="l1pdc8-1w wm-shadow"/><path class="nhm3kcoqx wm-k"/><path class="ovzt3sbip wm-k"/><path class="w87_sfbqc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:milk-engrave" /></template>
