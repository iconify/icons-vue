<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r0b91xnmk.css';
import '../../css/s/s4e00vcxg.css';
import '../../css/a/amvtuxlau.css';
import '../../css/i/ioasb8b3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="r0b91xnmk"/><path class="s4e00vcxg"/><path class="amvtuxlau"/><path class="ioasb8b3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pinecone" /></template>
