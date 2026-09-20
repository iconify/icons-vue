<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ug_skfbsy.css';
import '../../css/f/fwknfdbgo.css';
import '../../css/l/ledwm5bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ug_skfbsy"/><path class="fwknfdbgo"/><path clip-rule="evenodd" class="ledwm5bxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:washer-filled" /></template>
