<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tstyxkmej.css';
import '../../css/k/k3qcgxbnp.css';
import '../../css/i/iw07ocizs.css';
import '../../css/f/fmvl9jb-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tstyxkmej wm-k"/><path class="k3qcgxbnp wm-shadow"/><path class="iw07ocizs wm-k"/><path class="fmvl9jb-y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:refrigerator-engrave" /></template>
