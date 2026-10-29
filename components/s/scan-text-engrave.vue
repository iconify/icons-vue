<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/geik7_b-n.css';
import '../../css/h/h6pxxmopp.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/l/le4nw3b-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="geik7_b-n wm-k"/><path class="h6pxxmopp wm-shadow"/><path class="l9lv5_bcf wm-k"/><path class="le4nw3b-s wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-text-engrave" /></template>
