<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xhlos4b5a.css';
import '../../css/m/m31ubcc6y.css';
import '../../css/s/s9q4dubun.css';
import '../../css/z/z_224773w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-a xhlos4b5a"/><path class="m31ubcc6y wm-k"/><path class="s9q4dubun wm-a"/><path class="wm-s z_224773w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pichkari-sketch" /></template>
