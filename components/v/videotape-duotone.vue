<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hepm0sakq.css';
import '../../css/x/x4x127bql.css';
import '../../css/l/llhl7bcnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hepm0sakq"/><path class="x4x127bql"/><path class="llhl7bcnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:videotape-duotone" /></template>
