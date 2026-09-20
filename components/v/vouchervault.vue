<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quzxhsgmn.css';
import '../../css/o/o3q9lk3_p.css';
import '../../css/n/nw-hxrxlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="quzxhsgmn"/><path class="o3q9lk3_p"/><path class="nw-hxrxlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vouchervault" /></template>
