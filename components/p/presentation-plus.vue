<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwmzup7ha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwmzup7ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:presentation-plus" /></template>
