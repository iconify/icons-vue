<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1jeki3de.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w1jeki3de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-sharp-fill" /></template>
