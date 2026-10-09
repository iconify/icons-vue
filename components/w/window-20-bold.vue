<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/igsew81fb.css';
import '../../css/k/ki4_wwbbd.css';
import '../../css/e/eo_qvfbbf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="igsew81fb"/><path class="ki4_wwbbd"/><path class="eo_qvfbbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:window-20-bold" /></template>
