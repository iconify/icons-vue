<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/ze_-zp_7l.css';
import '../../css/c/csum4n-2b.css';
import '../../css/f/fvpfrkbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ze_-zp_7l"/><path class="csum4n-2b"/><path class="fvpfrkbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:screen-share-off" /></template>
