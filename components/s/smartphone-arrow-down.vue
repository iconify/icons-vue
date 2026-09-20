<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyg9p_u_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyg9p_u_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:smartphone-arrow-down" /></template>
