<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du5cymr0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du5cymr0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:truck-outline" /></template>
