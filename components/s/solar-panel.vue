<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg8_r5bqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg8_r5bqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:solar-panel" /></template>
