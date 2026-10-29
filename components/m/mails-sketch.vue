<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/ne_2utbrs.css';
import '../../css/l/l6-c-bchr.css';
import '../../css/r/r-2j79obd.css';
import '../../css/s/s9_1i3bbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ne_2utbrs"/><path class="l6-c-bchr wm-a"/><path class="r-2j79obd wm-k"/><path class="s9_1i3bbk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mails-sketch" /></template>
