<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qyt4n4h5f.css';
import '../../css/h/hid_d3u1e.css';
import '../../css/w/wf89k6buf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qyt4n4h5f"/><path class="hid_d3u1e"/><path class="wf89k6buf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimize-square-line-duotone" /></template>
