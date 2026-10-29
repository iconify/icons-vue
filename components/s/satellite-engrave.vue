<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o3ubp_41i.css';
import '../../css/m/md892_byh.css';
import '../../css/c/c17x734ui.css';
import '../../css/h/hov4pf25b.css';
import '../../css/k/kydla-v8g.css';
import '../../css/t/twlqflbgi.css';
import '../../css/p/pa-aaynvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o3ubp_41i wm-k"/><path class="md892_byh wm-a"/><path class="c17x734ui wm-s"/><path class="hov4pf25b wm-shadow"/><path class="kydla-v8g wm-k"/><path class="twlqflbgi wm-a"/><path class="pa-aaynvi wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:satellite-engrave" /></template>
