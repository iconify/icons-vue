<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv20g440o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv20g440o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sim-card-fill-round" /></template>
