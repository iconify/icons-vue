<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhc5k_b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhc5k_b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:wall-spot" /></template>
