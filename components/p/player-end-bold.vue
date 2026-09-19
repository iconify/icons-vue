<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3kb4cgpl.css';
import '../../css/b/brmvurbdu.css';
import '../../css/p/p69wevbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="r3kb4cgpl"><path class="brmvurbdu"/><path class="p69wevbnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-end-bold" /></template>
