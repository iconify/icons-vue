<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vs-iz_bnz.css';
import '../../css/x/xpx-tzx3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="ft5dv1b6b"><path class="vs-iz_bnz"/><path clip-rule="evenodd" class="xpx-tzx3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:user-white-filled" /></template>
