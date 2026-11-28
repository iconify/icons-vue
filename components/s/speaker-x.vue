<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inkxf6bcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inkxf6bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:speaker-x" /></template>
