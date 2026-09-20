<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0-g18vbb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0-g18vbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:pentagon-line" /></template>
