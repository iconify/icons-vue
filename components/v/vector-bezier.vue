<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb-4ft_ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-4ft_ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vector-bezier" /></template>
