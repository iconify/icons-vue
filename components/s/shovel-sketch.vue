<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nsi8if9vq.css';
import '../../css/t/t1xreqb-l.css';
import '../../css/l/l31wd34jz.css';
import '../../css/s/sd3hx-buh.css';
import '../../css/i/i37y9wb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nsi8if9vq"/><path class="t1xreqb-l wm-k"/><path class="l31wd34jz wm-a"/><path class="sd3hx-buh wm-k"/><path class="i37y9wb6u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shovel-sketch" /></template>
