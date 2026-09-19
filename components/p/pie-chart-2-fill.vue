<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9srj5bbq.css';
import '../../css/w/w81_4cfys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9srj5bbq"/><path class="w81_4cfys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:pie-chart-2-fill" /></template>
