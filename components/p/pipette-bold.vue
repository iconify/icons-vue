<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hko-q4lad.css';
import '../../css/u/ujph6vdwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hko-q4lad"/><path class="ujph6vdwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pipette-bold" /></template>
