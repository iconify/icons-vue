<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m06afk08h.css';
import '../../css/u/u50bmlwji.css';
import '../../css/d/d_i5s9b1t.css';
import '../../css/s/skp8tjssj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m06afk08h"/><path class="u50bmlwji"/><path class="d_i5s9b1t"/><path class="skp8tjssj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-pen-duotone" /></template>
