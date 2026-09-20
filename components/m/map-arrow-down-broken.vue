<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_uvrp5iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_uvrp5iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-down-broken" /></template>
