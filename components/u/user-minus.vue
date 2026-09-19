<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz-euib1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz-euib1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:user-minus" /></template>
