<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/evs7p7bus.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evs7p7bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:star-half-full" /></template>
