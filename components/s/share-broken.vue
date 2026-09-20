<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wjw99lb2m.css';
import '../../css/n/nk62zxbpn.css';
import '../../css/a/amsssrbtq.css';
import '../../css/i/it0o6lbdj.css';
import '../../css/o/olbluib9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wjw99lb2m"/><path class="nk62zxbpn"/><path class="amsssrbtq"/><path class="it0o6lbdj"/><path class="olbluib9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:share-broken" /></template>
