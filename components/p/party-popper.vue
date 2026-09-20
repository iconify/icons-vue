<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu8cdcbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu8cdcbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:party-popper" /></template>
