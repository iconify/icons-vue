<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oedcq-3gq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oedcq-3gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-gondola" /></template>
