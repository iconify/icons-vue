<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/in0jghbyd.css';
import '../../css/a/ardd_2b9b.css';
import '../../css/y/ya7jsccar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="in0jghbyd"/><path class="ardd_2b9b"/><path class="ya7jsccar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:master-card" /></template>
