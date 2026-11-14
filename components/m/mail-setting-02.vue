<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tlpmv6b8k.css';
import '../../css/d/df-j23bjo.css';
import '../../css/n/nxsctgbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tlpmv6b8k"/><path class="df-j23bjo"/><path class="nxsctgbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mail-setting-02" /></template>
