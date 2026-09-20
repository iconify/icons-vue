<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r7t7hwb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7t7hwb5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-gondola-full" /></template>
