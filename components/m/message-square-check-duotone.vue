<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/z51z6b_cv.css';
import '../../css/i/iym-rnbyp.css';
import '../../css/r/re7_rlvjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z51z6b_cv"/><path class="iym-rnbyp"/><path class="re7_rlvjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:message-square-check-duotone" /></template>
