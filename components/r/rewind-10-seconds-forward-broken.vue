<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tgcis5bxj.css';
import '../../css/g/gj9cr867l.css';
import '../../css/t/t8nvgqtdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tgcis5bxj"/><path class="gj9cr867l"/><path class="t8nvgqtdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-10-seconds-forward-broken" /></template>
