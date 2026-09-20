<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buyn9_bcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buyn9_bcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:train-car-passenger-door" /></template>
