<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ef4973xtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ef4973xtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:projector-screen-variant" /></template>
