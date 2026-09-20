<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/z/zcsjmmbtn.css';
import '../../css/r/rn72_7b7r.css';
import '../../css/f/f4vx4ccga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zcsjmmbtn"/><path class="rn72_7b7r"/><path class="f4vx4ccga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:music-note-off-sharp-duotone" /></template>
