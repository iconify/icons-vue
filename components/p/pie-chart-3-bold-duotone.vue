<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5pd03bym.css';
import '../../css/i/imsrai5rb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5pd03bym"/><path clip-rule="evenodd" class="imsrai5rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-3-bold-duotone" /></template>
