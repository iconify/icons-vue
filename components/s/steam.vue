<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q75sdk05z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":400};
const content = `<path class="q75sdk05z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:steam" /></template>
