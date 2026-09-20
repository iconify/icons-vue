<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fheh_03mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fheh_03mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-remove-bold" /></template>
