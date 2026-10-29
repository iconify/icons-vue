<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qvvkxkbcb.css';
import '../../css/s/szmghdbuf.css';
import '../../css/c/cuwghopiv.css';
import '../../css/q/q-90hqaaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qvvkxkbcb"/><path class="szmghdbuf wm-a"/><path class="cuwghopiv wm-k"/><path class="q-90hqaaz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:square-plus-sketch" /></template>
