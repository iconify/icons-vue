<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mhy19cc_w.css';
import '../../css/l/lx9et69ph.css';
import '../../css/e/e_onljbso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mhy19cc_w"/><path class="lx9et69ph"/><path class="e_onljbso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:printer-minimalistic-bold" /></template>
