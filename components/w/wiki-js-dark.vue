<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfj6s_bbb.css';
import '../../css/w/wsi6v13mq.css';
import '../../css/h/h_1tt7l9g.css';
import '../../css/p/pfrpmpb1c.css';
import '../../css/n/nul8knx4i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xfj6s_bbb"/><path class="wsi6v13mq"/><path class="h_1tt7l9g"/><path class="pfrpmpb1c"/><path class="nul8knx4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:wiki-js-dark" /></template>
