<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/emsr7ugpn.css';
import '../../css/i/iokftfwqy.css';
import '../../css/e/e-0e7kekg.css';
import '../../css/o/oqdxdpjwb.css';
import '../../css/b/bb8vnzh5z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="emsr7ugpn wm-k"/><path class="iokftfwqy wm-a"/><path class="e-0e7kekg wm-shadow"/><path class="oqdxdpjwb wm-k"/><path class="bb8vnzh5z wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:percent-engrave" /></template>
