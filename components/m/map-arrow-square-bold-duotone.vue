<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/os7xz0mqz.css';
import '../../css/f/f3axzccsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="os7xz0mqz"/><path class="f3axzccsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-square-bold-duotone" /></template>
