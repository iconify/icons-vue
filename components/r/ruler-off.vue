<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di4g56bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di4g56bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ruler-off" /></template>
