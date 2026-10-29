<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cql4d7ioj.css';
import '../../css/s/s95_oac6y.css';
import '../../css/o/o2_1jsbel.css';
import '../../css/k/kl1tskb-o.css';
import '../../css/x/xmw26lbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cql4d7ioj"/><path class="s95_oac6y wm-k"/><path class="o2_1jsbel wm-k"/><path class="kl1tskb-o wm-k"/><path class="wm-k xmw26lbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-round-sketch" /></template>
