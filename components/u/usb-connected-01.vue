<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/e03v5bc6t.css';
import '../../css/q/q9nl-gxlx.css';
import '../../css/p/psgm4limd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="e03v5bc6t"/><path class="q9nl-gxlx"/><path class="psgm4limd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:usb-connected-01" /></template>
