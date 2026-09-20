<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmw8czbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmw8czbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-plus-sharp" /></template>
