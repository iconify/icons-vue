<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tlsu4zyio.css';
import '../../css/h/h2c03wb3v.css';
import '../../css/i/il3hrdb7s.css';
import '../../css/s/spnf93r-f.css';
import '../../css/x/xh76--bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tlsu4zyio wm-k"/><path class="h2c03wb3v wm-s"/><path class="il3hrdb7s wm-shadow"/><path class="spnf93r-f wm-k"/><path class="wm-s xh76--bfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-forwarded-engrave" /></template>
