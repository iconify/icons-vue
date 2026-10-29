<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ck55j8b8a.css';
import '../../css/q/qib6t71cp.css';
import '../../css/l/lmo_-j63h.css';
import '../../css/w/wmvanjksm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ck55j8b8a wm-k"/><path class="qib6t71cp wm-a"/><path class="lmo_-j63h wm-k"/><path class="wm-a wmvanjksm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:recycle-sketch" /></template>
