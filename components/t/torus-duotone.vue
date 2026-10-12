<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h70jplbos.css';
import '../../css/r/rpzhmhbyx.css';
import '../../css/q/qul_7homc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="h70jplbos"/><path class="rpzhmhbyx"/><path class="qul_7homc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:torus-duotone" /></template>
