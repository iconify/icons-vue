<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km9qluwhp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="km9qluwhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pathfinder-unite-bold" /></template>
