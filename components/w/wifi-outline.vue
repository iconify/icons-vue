<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss6umgmez.css';
import '../../css/x/xelml5b_j.css';
import '../../css/u/u51rzi9rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ss6umgmez"/><path class="xelml5b_j"/><path class="u51rzi9rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:wifi-outline" /></template>
