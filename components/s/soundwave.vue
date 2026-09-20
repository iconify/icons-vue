<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srfajrbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srfajrbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:soundwave" /></template>
