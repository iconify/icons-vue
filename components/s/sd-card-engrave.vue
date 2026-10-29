<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jd1z6xbjn.css';
import '../../css/v/vg3x0nbkd.css';
import '../../css/a/abasntp2y.css';
import '../../css/g/go3ojebxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jd1z6xbjn wm-k"/><path class="vg3x0nbkd wm-shadow"/><path class="abasntp2y wm-k"/><path class="go3ojebxo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sd-card-engrave" /></template>
