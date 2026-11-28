<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m16j0vbtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m16j0vbtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:microwave-clock" /></template>
