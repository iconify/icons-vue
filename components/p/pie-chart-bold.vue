<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqk9_4b2a.css';
import '../../css/r/r-rt-5hka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gqk9_4b2a"/><path class="r-rt-5hka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pie-chart-bold" /></template>
