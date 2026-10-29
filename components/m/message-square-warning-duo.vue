<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pjocyqddu.css';
import '../../css/p/pi9dym7jx.css';
import '../../css/e/ee_t7pb7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pjocyqddu"/><path class="pi9dym7jx wm-a"/><path class="ee_t7pb7v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-square-warning-duo" /></template>
