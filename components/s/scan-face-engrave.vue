<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/ggdm2b8ta.css';
import '../../css/h/h567jqbwk.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/z/zpu53zwhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ggdm2b8ta wm-k"/><path class="h567jqbwk wm-shadow"/><path class="l9lv5_bcf wm-k"/><path class="wm-a zpu53zwhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-face-engrave" /></template>
