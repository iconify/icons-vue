<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8t4grbmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8t4grbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:planet-minus" /></template>
