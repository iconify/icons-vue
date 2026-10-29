<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nd5v5hbdl.css';
import '../../css/d/dmmnz5brv.css';
import '../../css/b/bih0_hbcd.css';
import '../../css/f/f_o9585tx.css';
import '../../css/z/z_leajngu.css';
import '../../css/j/j7ffi82vm.css';
import '../../css/n/nz03h8bkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nd5v5hbdl wm-k"/><path class="dmmnz5brv wm-a"/><path class="bih0_hbcd wm-shadow"/><path class="f_o9585tx wm-k"/><path class="wm-a z_leajngu"/><path class="j7ffi82vm wm-k"/><path class="nz03h8bkr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minimize-2-engrave" /></template>
