<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b2b3vubia.css';
import '../../css/t/tfnc91bfv.css';
import '../../css/n/nn2f9gisi.css';
import '../../css/d/dk-3u6b9m.css';
import '../../css/v/vvpcfyjlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b2b3vubia"/><path class="tfnc91bfv wm-shadow"/><path class="nn2f9gisi"/><path class="dk-3u6b9m"/><path class="vvpcfyjlf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:spider-engrave" /></template>
