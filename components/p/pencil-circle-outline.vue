<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxo87q4fu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxo87q4fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pencil-circle-outline" /></template>
