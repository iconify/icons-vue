<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_pkvebfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_pkvebfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:percent-line" /></template>
