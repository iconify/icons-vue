<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gig7apbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gig7apbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:road-map-fill" /></template>
