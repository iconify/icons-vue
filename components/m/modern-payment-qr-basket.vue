<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mvd1m8bez.css';
import '../../css/q/qjykfwbex.css';
import '../../css/n/npm16tm7n.css';
import '../../css/n/nsefvcihq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mvd1m8bez"/><path class="qjykfwbex"/><path class="npm16tm7n"/><path class="nsefvcihq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:modern-payment-qr-basket" /></template>
