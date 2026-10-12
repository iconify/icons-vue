<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hmfhugg_x.css';
import '../../css/m/m6mj_obaa.css';
import '../../css/f/fn8tddcxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hmfhugg_x"/><path class="m6mj_obaa"/><path class="fn8tddcxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:thermometer-sun-duotone" /></template>
