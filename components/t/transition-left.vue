<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kds9smf3q.css';
import '../../css/n/nrg0twbrt.css';
import '../../css/y/y_r1fbgtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kds9smf3q"/><path class="nrg0twbrt"/><path class="y_r1fbgtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:transition-left" /></template>
