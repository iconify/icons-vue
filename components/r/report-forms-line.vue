<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxm07dm6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxm07dm6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:report-forms-line" /></template>
