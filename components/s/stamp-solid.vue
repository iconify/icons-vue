<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/s/s4smqub5w.css';
import '../../css/o/oycvfsbjh.css';
import '../../css/g/g72t0rbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="s4smqub5w"/><path class="oycvfsbjh wm-a"/><path class="g72t0rbmk wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stamp-solid" /></template>
