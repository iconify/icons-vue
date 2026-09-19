<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7n010b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7n010b3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:oracle" /></template>
