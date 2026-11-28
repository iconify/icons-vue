<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuoeadbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuoeadbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:robot-vacuum-pause" /></template>
