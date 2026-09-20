<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzvv3hf9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mzvv3hf9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-2-horizontal-start-fill" /></template>
