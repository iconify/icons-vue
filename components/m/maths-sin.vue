<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgl2ijbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgl2ijbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:maths-sin" /></template>
