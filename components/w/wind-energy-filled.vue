<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjkl8cb9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjkl8cb9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:wind-energy-filled" /></template>
