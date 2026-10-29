<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kj_zj2cjc.css';
import '../../css/s/si9s5fb2e.css';
import '../../css/w/w4vj0mdzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kj_zj2cjc wm-k"/><path class="si9s5fb2e wm-k"/><path class="w4vj0mdzj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:repeat-sketch" /></template>
