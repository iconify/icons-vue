<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ajrvvrbka.css';
import '../../css/j/j_3xzu17f.css';
import '../../css/j/jh3gw-bag.css';
import '../../css/i/iyexf9bri.css';
import '../../css/y/y2dq4-b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ajrvvrbka wm-k"/><path class="j_3xzu17f wm-a"/><path class="jh3gw-bag wm-shadow"/><path class="iyexf9bri wm-k"/><path class="wm-a y2dq4-b3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ship-engrave" /></template>
