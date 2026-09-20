<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e841m2env.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e841m2env"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:snow-solid" /></template>
