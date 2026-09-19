<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2u2u_bjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q2u2u_bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:solar-energy-filled" /></template>
