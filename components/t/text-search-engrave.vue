<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i_gbtq9gj.css';
import '../../css/v/vm_vkq69s.css';
import '../../css/l/l0orl0b7t.css';
import '../../css/g/gz4rmvf3e.css';
import '../../css/w/wtwdiqbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i_gbtq9gj wm-k"/><path class="vm_vkq69s wm-a"/><path class="l0orl0b7t wm-shadow"/><path class="gz4rmvf3e wm-k"/><path class="wm-a wtwdiqbwi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:text-search-engrave" /></template>
