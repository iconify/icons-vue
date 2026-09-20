<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg59nlbhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rg59nlbhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:number-seven-circle-bold" /></template>
