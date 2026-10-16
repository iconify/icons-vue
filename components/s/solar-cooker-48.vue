<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr71bdctn.css';
import '../../css/k/kezkawjrn.css';
import '../../css/c/czpegmbjb.css';
import '../../css/s/ss_828btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wr71bdctn"/><path class="kezkawjrn"/><path class="czpegmbjb"/><path class="ss_828btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-cooker-48" /></template>
