<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l9vmhfb_s.css';
import '../../css/r/r3yr01bjg.css';
import '../../css/x/xrfn3bcyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l9vmhfb_s"/><path class="r3yr01bjg wm-shadow"/><path class="xrfn3bcyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-engrave" /></template>
