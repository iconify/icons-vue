<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdj631veg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdj631veg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:server-network" /></template>
