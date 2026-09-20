<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io9g4snny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io9g4snny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pills3-filled" /></template>
