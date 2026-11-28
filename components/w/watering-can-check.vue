<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ird1tc7rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ird1tc7rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:watering-can-check" /></template>
