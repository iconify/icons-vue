<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1hpkybtj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1hpkybtj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:police-car-fill" /></template>
