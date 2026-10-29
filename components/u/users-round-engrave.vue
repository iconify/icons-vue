<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sirq2-j2p.css';
import '../../css/z/z4paenj8z.css';
import '../../css/l/lhlq9zetp.css';
import '../../css/t/t_g_x1biv.css';
import '../../css/c/c-t_59bnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sirq2-j2p wm-k"/><path class="wm-a z4paenj8z"/><path class="lhlq9zetp wm-shadow"/><path class="t_g_x1biv wm-k"/><path class="c-t_59bnx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:users-round-engrave" /></template>
