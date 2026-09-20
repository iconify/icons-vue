<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl7fttbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl7fttbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sun-cloudy-fill" /></template>
