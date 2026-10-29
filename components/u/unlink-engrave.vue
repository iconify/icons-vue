<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b4yu8ubta.css';
import '../../css/d/dik90hxbh.css';
import '../../css/r/ruuozac9m.css';
import '../../css/e/e0izkne-h.css';
import '../../css/u/unkvyfx-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b4yu8ubta wm-k"/><path class="dik90hxbh wm-s"/><path class="ruuozac9m wm-shadow"/><path class="e0izkne-h wm-k"/><path class="unkvyfx-l wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:unlink-engrave" /></template>
