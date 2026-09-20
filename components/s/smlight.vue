<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh1j5ublv.css';
import '../../css/d/dzvme4b_s.css';
import '../../css/z/z8__jxbtc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="uh1j5ublv"/><circle class="dzvme4b_s"/><circle class="z8__jxbtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:smlight" /></template>
