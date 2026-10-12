<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q0_9pqbee.css';
import '../../css/u/ull_34beu.css';
import '../../css/u/uswle2b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q0_9pqbee"/><path class="ull_34beu"/><path class="uswle2b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-mouse-pointer-duotone" /></template>
