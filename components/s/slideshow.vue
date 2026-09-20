<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9oq99bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9oq99bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:slideshow" /></template>
