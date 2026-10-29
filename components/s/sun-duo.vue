<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/ll9crmb_e.css';
import '../../css/z/zs295v-ni.css';
import '../../css/y/yi23eea4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ll9crmb_e"/><path class="wm-a zs295v-ni"/><path class="yi23eea4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sun-duo" /></template>
