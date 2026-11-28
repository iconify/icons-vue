<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_z-sjwmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_z-sjwmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:map-x" /></template>
