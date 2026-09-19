<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/t8tdq3vdl.css';
import '../../css/m/mnjer5bid.css';
import '../../css/e/e7-t_vbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="t8tdq3vdl"/><rect class="mnjer5bid"/><circle class="e7-t_vbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:wallet-outline" /></template>
