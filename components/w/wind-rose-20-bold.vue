<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-ons0b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q-ons0b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-rose-20-bold" /></template>
