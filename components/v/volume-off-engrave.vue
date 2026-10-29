<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f6jp3jbsz.css';
import '../../css/l/l8c4rkbqx.css';
import '../../css/y/y9npttv3e.css';
import '../../css/s/st-oxhb_e.css';
import '../../css/d/d074ckbgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f6jp3jbsz wm-k"/><path class="l8c4rkbqx wm-s"/><path class="wm-shadow y9npttv3e"/><path class="st-oxhb_e wm-k"/><path class="d074ckbgd wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:volume-off-engrave" /></template>
