<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/iqxi9pbtv.css';
import '../../css/l/lrra40ljv.css';
import '../../css/k/ku4pnpblw.css';
import '../../css/m/mt--exbgb.css';
import '../../css/i/iln71zb0h.css';
import '../../css/o/o7p-pybex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="iqxi9pbtv wm-k"/><path class="lrra40ljv wm-a"/><path class="ku4pnpblw wm-s"/><path class="mt--exbgb wm-k"/><path class="iln71zb0h wm-a"/><path class="o7p-pybex wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:spell-check-sketch" /></template>
