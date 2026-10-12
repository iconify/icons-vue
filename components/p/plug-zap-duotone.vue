<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tnbdi8n3b.css';
import '../../css/i/i6u14jbud.css';
import '../../css/s/s8riu9c1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tnbdi8n3b"/><path class="i6u14jbud"/><path class="s8riu9c1v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:plug-zap-duotone" /></template>
