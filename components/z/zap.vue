<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kl1yn4h8b.css';
import '../../css/j/jjtrb7gqz.css';
import '../../css/n/nsliu1bpn.css';
import '../../css/x/x9bh9czof.css';
import '../../css/s/swa05bbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kl1yn4h8b wm-k"/><path class="jjtrb7gqz wm-k"/><path class="nsliu1bpn wm-k"/><path class="wm-shine x9bh9czof"/><path class="swa05bbqv wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:zap" /></template>
