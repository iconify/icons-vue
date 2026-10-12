<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i5j7aexcp.css';
import '../../css/l/luxc5ghbs.css';
import '../../css/r/rojk_bdub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i5j7aexcp"/><path class="luxc5ghbs"/><path class="rojk_bdub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tag-duotone" /></template>
