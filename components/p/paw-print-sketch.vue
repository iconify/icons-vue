<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/d4npf2b7l.css';
import '../../css/a/aq2xiwpnd.css';
import '../../css/e/ex3s_hbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="d4npf2b7l"/><path class="aq2xiwpnd wm-k"/><path class="ex3s_hbnx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paw-print-sketch" /></template>
