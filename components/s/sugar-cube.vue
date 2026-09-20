<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q7i33_fpe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q7i33_fpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sugar-cube" /></template>
