<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qce6_bb4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qce6_bb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:pie-chart" /></template>
