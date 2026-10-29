<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dqi4ifb3t.css';
import '../../css/n/n-n2__xqz.css';
import '../../css/s/skgel1llp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dqi4ifb3t"/><path class="n-n2__xqz wm-shadow"/><path class="skgel1llp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:playground-engrave" /></template>
