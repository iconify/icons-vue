<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vt19b-b7a.css';
import '../../css/x/xm1qpqbof.css';
import '../../css/d/d2omlvbzu.css';
import '../../css/e/eqcaaebyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vt19b-b7a wm-k"/><path class="wm-a xm1qpqbof"/><path class="d2omlvbzu wm-k"/><path class="eqcaaebyw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tennis-sketch" /></template>
