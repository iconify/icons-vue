<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-l1pd0_w.css';
import '../../css/a/aghnw_bgv.css';
import '../../css/m/mcl_-ke3h.css';
import '../../css/a/ahtm1qbts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path clip-rule="evenodd" class="aghnw_bgv"/><path class="mcl_-ke3h"/><path clip-rule="evenodd" class="ahtm1qbts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:round-flask-solid" /></template>
