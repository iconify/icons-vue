<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/idqwhrbft.css';
import '../../css/k/kd3dk6bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="idqwhrbft"/><path clip-rule="evenodd" class="kd3dk6bth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:nrksuper-avatar-expressive" /></template>
