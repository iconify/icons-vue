<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhi603tyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhi603tyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage-solid" /></template>
