<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vkklw8pdh.css';
import '../../css/s/s99h_lbvn.css';
import '../../css/x/xwd8aibef.css';
import '../../css/k/kzqm9y_ar.css';
import '../../css/m/miaw0lbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vkklw8pdh wm-k"/><path class="s99h_lbvn wm-a"/><path class="wm-shadow xwd8aibef"/><path class="kzqm9y_ar wm-k"/><path class="miaw0lbio wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pizza-engrave" /></template>
