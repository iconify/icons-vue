<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r1gp5-u1c.css';
import '../../css/m/myw_a-bni.css';
import '../../css/k/kb9eddb8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r1gp5-u1c"/><path class="myw_a-bni"/><path class="kb9eddb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:store-duotone" /></template>
