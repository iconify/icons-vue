<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kksoo5x2s.css';
import '../../css/i/i41888b_p.css';
import '../../css/m/mx6o2rv6q.css';
import '../../css/s/s84s_lbks.css';
import '../../css/x/xnsux1j5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kksoo5x2s"/><path class="i41888b_p"/><path class="mx6o2rv6q"/><path class="s84s_lbks"/><path class="xnsux1j5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vpn-sentinel" /></template>
