<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihbrj940g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihbrj940g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:stethoscope-check" /></template>
