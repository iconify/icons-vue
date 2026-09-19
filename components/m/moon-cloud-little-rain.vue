<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/w0n0gzb6b.css';
import '../../css/t/t1bp93bkt.css';
import '../../css/h/hagc2nfwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="w0n0gzb6b"/><path class="t1bp93bkt"/><path class="hagc2nfwh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:moon-cloud-little-rain" /></template>
