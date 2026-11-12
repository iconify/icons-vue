<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc--wpv5i.css';
import '../../css/f/f-c80ro0i.css';
import '../../css/h/h4n6ekwws.css';
import '../../css/a/a7mbluw4j.css';
import '../../css/t/txnq4cljl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVGN9EiDdzR" x1="-51.3" x2="563.3" y1="78.6" y2="433.4" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="f-c80ro0i"/></linearGradient><path fill="url(#SVGN9EiDdzR)" class="h4n6ekwws"/><path class="a7mbluw4j"/><path class="txnq4cljl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opengrammar-light" /></template>
