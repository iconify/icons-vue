<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw53-sbdu.css';
import '../../css/b/b_6nlsbae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lw53-sbdu"/><path class="b_6nlsbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:solar-meter-48" /></template>
