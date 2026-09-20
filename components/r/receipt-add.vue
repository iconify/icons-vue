<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8oo7gb6g.css';
import '../../css/k/k7ry2_vew.css';
import '../../css/y/yk_u-tb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="k7ry2_vew"/><path class="yk_u-tb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="marketeq:receipt-add" /></template>
