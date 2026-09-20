<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9m7mj39d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9m7mj39d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-up" /></template>
