<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/h8pt52bcc.css';
import '../../css/b/bopi9b9jn.css';
import '../../css/f/fxwnb7vgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h8pt52bcc"/><circle class="bopi9b9jn"/><circle class="fxwnb7vgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:spline-pointer" /></template>
