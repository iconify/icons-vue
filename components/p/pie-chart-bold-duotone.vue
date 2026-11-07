<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hw6cz2bya.css';
import '../../css/g/gussmibdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hw6cz2bya"/><path class="gussmibdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-bold-duotone" /></template>
