<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nq40t8vnp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nq40t8vnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:percentage-diamond-solid" /></template>
