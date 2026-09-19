<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsew7abve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsew7abve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:power-panel-logo" /></template>
