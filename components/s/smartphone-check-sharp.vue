<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk6tewbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk6tewbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-check-sharp" /></template>
