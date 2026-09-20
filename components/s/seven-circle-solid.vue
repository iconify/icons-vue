<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucj6lf7oo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucj6lf7oo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:seven-circle-solid" /></template>
