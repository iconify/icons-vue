<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/tlsu4zyio.css';
import '../../css/a/akuc8w9ak.css';
import '../../css/a/a-sal1mlb.css';
import '../../css/s/spnf93r-f.css';
import '../../css/s/slzsfcc0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="tlsu4zyio wm-k"/><path class="akuc8w9ak wm-s"/><path class="a-sal1mlb wm-shadow"/><path class="spnf93r-f wm-k"/><path class="slzsfcc0u wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-missed-engrave" /></template>
