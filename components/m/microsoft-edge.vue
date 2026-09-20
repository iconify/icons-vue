<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esf_cdlak.css';
import '../../css/d/dxwmkobkt.css';
import '../../css/m/m79ns814e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esf_cdlak"/><path class="dxwmkobkt"/><path class="m79ns814e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:microsoft-edge" /></template>
