<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn3mo9bss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dn3mo9bss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:pi-network" /></template>
