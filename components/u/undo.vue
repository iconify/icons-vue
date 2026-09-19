<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrmfs0crz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrmfs0crz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:undo" /></template>
