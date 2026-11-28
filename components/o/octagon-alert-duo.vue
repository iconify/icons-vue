<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slknnlbbl.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/u/uxfqx7b8a.css';
import '../../css/w/wkbb-c3nd.css';
import '../../css/l/ln33cc_mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary slknnlbbl"/><g class="dt0cm9dhy primary"><path class="uxfqx7b8a"/><path class="wkbb-c3nd"/><path class="ln33cc_mx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:octagon-alert-duo" /></template>
