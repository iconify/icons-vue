<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/job_fgb5d.css';
import '../../css/e/es4tnviht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="job_fgb5d"/><path class="es4tnviht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pallet-20" /></template>
