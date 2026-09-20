<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhdy70bcr.css';
import '../../css/l/l2895_5bw.css';
import '../../css/f/fo69pib0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uhdy70bcr"/><path class="l2895_5bw"/><path class="fo69pib0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:scrutiny" /></template>
