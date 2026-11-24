<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak3byoaiu.css';
import '../../css/q/qsjon_xqs.css';
import '../../css/e/es1i79bpz.css';
import '../../css/l/lbss1-iny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="ak3byoaiu"/><rect class="qsjon_xqs"/><rect class="es1i79bpz"/><rect class="lbss1-iny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:opencaptions" /></template>
