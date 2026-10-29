<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pjocyqddu.css';
import '../../css/t/t6njcbc0d.css';
import '../../css/e/ee_t7pb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pjocyqddu"/><path class="t6njcbc0d wm-a"/><path class="ee_t7pb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-x-duo" /></template>
