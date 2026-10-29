<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nkv6ox-um.css';
import '../../css/a/aewt85m1n.css';
import '../../css/t/tw2yi0b2x.css';
import '../../css/g/gsmwzvboi.css';
import '../../css/n/n2b3okm6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nkv6ox-um"/><path class="aewt85m1n wm-k"/><path class="tw2yi0b2x wm-k"/><path class="gsmwzvboi wm-a"/><path class="n2b3okm6x wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:piggy-bank-sketch" /></template>
