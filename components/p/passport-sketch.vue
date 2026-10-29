<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/sul672bkd.css';
import '../../css/e/eeypgqbjc.css';
import '../../css/d/dqwry0bep.css';
import '../../css/m/me_u55doq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="sul672bkd"/><path class="eeypgqbjc wm-a"/><path class="dqwry0bep wm-k"/><path class="me_u55doq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:passport-sketch" /></template>
