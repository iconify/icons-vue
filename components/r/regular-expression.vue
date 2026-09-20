<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmtaqcosj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmtaqcosj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:regular-expression" /></template>
