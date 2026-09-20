<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ye2lhacqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ye2lhacqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-down-fill" /></template>
