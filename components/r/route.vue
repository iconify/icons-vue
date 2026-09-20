<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tke4h5b0x.css';
import '../../css/c/c5kr73bow.css';
import '../../css/u/ugw1omula.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="tke4h5b0x"/><path class="c5kr73bow"/><circle class="ugw1omula"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:route" /></template>
