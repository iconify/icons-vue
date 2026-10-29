<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hu0864bjy.css';
import '../../css/o/o-jk2xaue.css';
import '../../css/w/wg2oucbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hu0864bjy"/><path class="o-jk2xaue wm-k"/><path class="wg2oucbbj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microwave-sketch" /></template>
