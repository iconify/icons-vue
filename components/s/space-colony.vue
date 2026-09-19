<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/r/rwrx43b6h.css';
import '../../css/i/iu1duub_r.css';
import '../../css/n/nqd8rfb-h.css';
import '../../css/i/irduxyb1o.css';
import '../../css/s/sl21rfjyl.css';
import '../../css/i/ii0wlebwq.css';
import '../../css/c/cejfnfb0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="rwrx43b6h"/><path class="iu1duub_r"/><path class="nqd8rfb-h"/><path class="irduxyb1o"/><path class="sl21rfjyl"/><path class="ii0wlebwq"/><path class="cejfnfb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:space-colony" /></template>
