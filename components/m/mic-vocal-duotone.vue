<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x4_zp4ble.css';
import '../../css/s/s9m-tlb3z.css';
import '../../css/g/gbkuyab6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x4_zp4ble"/><path class="s9m-tlb3z"/><path class="gbkuyab6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mic-vocal-duotone" /></template>
