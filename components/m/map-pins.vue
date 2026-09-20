<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ul8_q0b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ul8_q0b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:map-pins" /></template>
