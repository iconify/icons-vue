<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg16eyxff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg16eyxff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:oven-mitt" /></template>
