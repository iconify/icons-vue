<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2d-o_bov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2d-o_bov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:question-square-solid" /></template>
