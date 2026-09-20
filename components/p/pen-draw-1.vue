<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm70g7bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm70g7bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pen-draw-1" /></template>
