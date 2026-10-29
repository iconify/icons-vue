<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nkg1agbyx.css';
import '../../css/g/gxqk5yt0t.css';
import '../../css/t/txnheqbrz.css';
import '../../css/l/l_1qa9brg.css';
import '../../css/d/duzqyrybg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nkg1agbyx wm-k"/><path class="gxqk5yt0t wm-s"/><path class="txnheqbrz wm-k"/><path class="l_1qa9brg wm-a"/><path class="duzqyrybg wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sunset-sketch" /></template>
