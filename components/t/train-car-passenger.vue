<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r55r7ibth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r55r7ibth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-passenger" /></template>
