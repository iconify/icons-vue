<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mytwn4byj.css';
import '../../css/m/mypwvhfpi.css';
import '../../css/t/tu05rhbbq.css';
import '../../css/n/n_u26bcvo.css';
import '../../css/b/b_9x90big.css';
import '../../css/f/fwq7t4hzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mytwn4byj"/><path class="mypwvhfpi wm-k"/><path class="tu05rhbbq wm-a"/><path class="n_u26bcvo wm-k"/><path class="b_9x90big wm-a"/><path class="fwq7t4hzk wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:party-popper-sketch" /></template>
