<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g9t5albup.css';
import '../../css/e/e1dpcubfa.css';
import '../../css/d/dw8rv-b5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g9t5albup"/><path class="e1dpcubfa"/><path class="dw8rv-b5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-start-duotone" /></template>
