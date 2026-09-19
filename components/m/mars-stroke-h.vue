<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mf7xaq13d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":24};
const content = `<path class="mf7xaq13d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:mars-stroke-h" /></template>
