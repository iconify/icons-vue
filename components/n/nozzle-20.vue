<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkmlt_lmx.css';
import '../../css/m/m4o-xp_cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hkmlt_lmx"/><path class="m4o-xp_cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nozzle-20" /></template>
