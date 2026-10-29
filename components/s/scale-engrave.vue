<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rbb3a5bie.css';
import '../../css/k/kjj_5s8ct.css';
import '../../css/a/ao54is99w.css';
import '../../css/k/k84vtocml.css';
import '../../css/b/bropegbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rbb3a5bie wm-k"/><path class="kjj_5s8ct wm-a"/><path class="ao54is99w wm-shadow"/><path class="k84vtocml wm-k"/><path class="bropegbcq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scale-engrave" /></template>
