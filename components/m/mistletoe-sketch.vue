<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jfu-tsbtl.css';
import '../../css/m/mh3_kgpzk.css';
import '../../css/d/dda-ttbbb.css';
import '../../css/n/nasfv3bad.css';
import '../../css/t/tpyqchb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jfu-tsbtl wm-k"/><path class="mh3_kgpzk wm-k"/><circle class="dda-ttbbb wm-s"/><circle class="nasfv3bad wm-s"/><circle class="tpyqchb3u wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mistletoe-sketch" /></template>
