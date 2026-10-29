<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/ps_iqbbjk.css';
import '../../css/n/ncja3g58k.css';
import '../../css/s/smuuuh87u.css';
import '../../css/y/yhnetzb3t.css';
import '../../css/k/kz28c1hto.css';
import '../../css/d/dlm7yr8dw.css';
import '../../css/w/wjyb9z-mn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ps_iqbbjk"/><path class="ncja3g58k wm-k"/><path class="smuuuh87u wm-a"/><path class="wm-s yhnetzb3t"/><path class="kz28c1hto wm-k"/><path class="dlm7yr8dw wm-a"/><path class="wjyb9z-mn wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:users-plus-sketch" /></template>
