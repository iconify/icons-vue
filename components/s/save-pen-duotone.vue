<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rbfxhrdcj.css';
import '../../css/r/rs2_d-b2c.css';
import '../../css/q/qwxvauhsb.css';
import '../../css/r/rbyrefbxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rbfxhrdcj"/><path class="rs2_d-b2c"/><path class="qwxvauhsb"/><path class="rbyrefbxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:save-pen-duotone" /></template>
