<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uldvl70py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uldvl70py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motorway" /></template>
