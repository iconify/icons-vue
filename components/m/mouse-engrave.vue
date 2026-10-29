<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sb5v5hbei.css';
import '../../css/o/oghnc41ik.css';
import '../../css/l/l7k0l-tlx.css';
import '../../css/m/mm8lkn_5j.css';
import '../../css/d/dxo27vb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sb5v5hbei wm-k"/><path class="oghnc41ik wm-a"/><path class="l7k0l-tlx wm-shadow"/><path class="mm8lkn_5j wm-k"/><path class="dxo27vb0f wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mouse-engrave" /></template>
