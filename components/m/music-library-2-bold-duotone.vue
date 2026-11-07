<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxpoqcbtn.css';
import '../../css/f/fgxux-b-v.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/h/huw4b6big.css';
import '../../css/m/mt3e7vqmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxpoqcbtn"/><path clip-rule="evenodd" class="fgxux-b-v"/><g class="xtpeb-edw"><path class="huw4b6big"/><path class="mt3e7vqmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-library-2-bold-duotone" /></template>
