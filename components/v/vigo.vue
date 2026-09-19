<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzlgly3ke.css';
import '../../css/q/qrhmcj17p.css';
import '../../css/i/i-dn492le.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="zzlgly3ke"><path class="qrhmcj17p"/><path class="i-dn492le"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:vigo" /></template>
