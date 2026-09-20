<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kinrhcbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kinrhcbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:map-pin-range-fill" /></template>
