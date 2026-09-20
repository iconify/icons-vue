<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnj_f4vdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hnj_f4vdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:wind-turbine" /></template>
