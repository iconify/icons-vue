<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s90-m48_g.css';
import '../../css/h/hfo9yibgw.css';
import '../../css/u/u9x-rxprv.css';
import '../../css/r/ryspfpb-k.css';
import '../../css/m/m5r_cxb1p.css';
import '../../css/v/v_xpk7b2g.css';
import '../../css/n/n5u9jb9by.css';
import '../../css/q/qrd1npbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s90-m48_g"/><path class="hfo9yibgw"/><path class="u9x-rxprv"/><path class="ryspfpb-k"/><path class="m5r_cxb1p"/><path class="v_xpk7b2g"/><path class="n5u9jb9by"/><path class="qrd1npbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:postbox" /></template>
