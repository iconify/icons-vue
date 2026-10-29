<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lm801wxba.css';
import '../../css/z/z-o_19xda.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lm801wxba wm-k"/><path class="wm-k z-o_19xda"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zap-off-duo" /></template>
