<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l546r6byy.css';
import '../../css/d/dqrzf1bnz.css';
import '../../css/a/avr8ui1vm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l546r6byy"/><path class="dqrzf1bnz"/><path class="avr8ui1vm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:plus-print" /></template>
