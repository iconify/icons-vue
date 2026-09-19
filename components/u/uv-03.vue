<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vygnzo2pp.css';
import '../../css/i/ibfbl8b6r.css';
import '../../css/g/g3t9fpbhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vygnzo2pp"/><path class="ibfbl8b6r"/><path class="g3t9fpbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:uv-03" /></template>
