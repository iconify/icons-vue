<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/aw7h4pbns.css';
import '../../css/q/q4vef2bkz.css';
import '../../css/x/xt16wcg7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="aw7h4pbns wm-k"/><path class="q4vef2bkz wm-shadow"/><path class="wm-k xt16wcg7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zap-engrave" /></template>
