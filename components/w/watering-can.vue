<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msy8anbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msy8anbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:watering-can" /></template>
