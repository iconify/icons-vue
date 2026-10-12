<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx1t0xbct.css';
import '../../css/u/u899ipb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kx1t0xbct"/><path class="u899ipb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:whiteboard-48-bold" /></template>
