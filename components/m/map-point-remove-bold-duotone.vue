<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ev04l0b7x.css';
import '../../css/n/npr104o_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ev04l0b7x"/><path class="npr104o_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-remove-bold-duotone" /></template>
