<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oaoax90by.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaoax90by"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:subway-fill" /></template>
