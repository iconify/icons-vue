<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/txn_7sbfw.css';
import '../../css/x/x3-9faclu.css';
import '../../css/w/wxwl6_qzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="txn_7sbfw"/><path class="wm-shadow x3-9faclu"/><path class="wxwl6_qzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-engrave" /></template>
