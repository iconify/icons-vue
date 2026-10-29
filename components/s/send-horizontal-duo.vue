<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/q_9pyo6hu.css';
import '../../css/h/h0rhmfbpn.css';
import '../../css/u/uu_zhdcpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="q_9pyo6hu"/><path class="h0rhmfbpn wm-a"/><path class="uu_zhdcpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-horizontal-duo" /></template>
