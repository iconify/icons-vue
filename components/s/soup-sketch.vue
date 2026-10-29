<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zkcgbk_eu.css';
import '../../css/z/zengsob3h.css';
import '../../css/e/e_aqre_dg.css';
import '../../css/n/n64u7efyk.css';
import '../../css/m/mb82hcb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="zkcgbk_eu"/><path class="wm-k zengsob3h"/><path class="e_aqre_dg wm-a"/><path class="n64u7efyk wm-k"/><path class="mb82hcb_w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:soup-sketch" /></template>
