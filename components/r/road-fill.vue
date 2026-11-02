<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omwgj_mcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omwgj_mcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:road-fill" /></template>
