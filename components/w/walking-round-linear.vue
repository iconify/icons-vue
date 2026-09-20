<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/if_w8upnf.css';
import '../../css/b/bqhqz_9_r.css';
import '../../css/k/kk6lmubmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="if_w8upnf"/><path class="bqhqz_9_r"/><path class="kk6lmubmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:walking-round-linear" /></template>
