<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxuzv3bfk.css';
import '../../css/o/oscggibnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sxuzv3bfk"/><path class="oscggibnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:webhook-48-bold" /></template>
