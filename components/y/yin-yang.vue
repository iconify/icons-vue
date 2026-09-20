<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/m/mwqyepbww.css';
import '../../css/i/ia0_hgbwx.css';
import '../../css/p/py15g5w5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="shu3xdl9q"/><circle class="mwqyepbww"/><path class="ia0_hgbwx"/><circle class="py15g5w5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:yin-yang" /></template>
