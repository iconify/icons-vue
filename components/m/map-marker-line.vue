<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/l/ld30g871v.css';
import '../../css/y/ywa5aqr7m.css';
import '../../css/x/xbhes0ulq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="ld30g871v"/><path class="ywa5aqr7m"/><path class="xbhes0ulq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:map-marker-line" /></template>
