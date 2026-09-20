<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-dyeon3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-dyeon3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:power-pole-asymmetric-armless" /></template>
