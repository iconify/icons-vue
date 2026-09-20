<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuz0hewbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuz0hewbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:scissors-2-fill" /></template>
