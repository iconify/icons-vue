<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/c05_9vbhx.css';
import '../../css/g/gi5g7lm5g.css';
import '../../css/h/hl7ikcc0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c05_9vbhx"/><path class="gi5g7lm5g"/><path class="hl7ikcc0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:users-round-collaboration-duotone" /></template>
