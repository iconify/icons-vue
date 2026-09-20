<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nn1itiinb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn1itiinb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:servicemark" /></template>
