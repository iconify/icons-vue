<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y41spbbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y41spbbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:podium-silver" /></template>
