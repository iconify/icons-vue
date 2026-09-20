<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fykkjg8af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fykkjg8af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-passenger-door-open" /></template>
