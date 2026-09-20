<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejoc73bsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejoc73bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-hopper-full" /></template>
