<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elu00db0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elu00db0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:map-pin-star" /></template>
