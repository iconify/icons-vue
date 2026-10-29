<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/o_7ga6bdw.css';
import '../../css/u/uh1_r9b4t.css';
import '../../css/v/va822-zkp.css';
import '../../css/g/g9l1osk0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="o_7ga6bdw wm-k"/><path class="uh1_r9b4t wm-k"/><path class="va822-zkp wm-a"/><path class="g9l1osk0p wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:poinsettia-sketch" /></template>
