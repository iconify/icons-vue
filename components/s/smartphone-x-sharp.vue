<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_hs7szqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_hs7szqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-x-sharp" /></template>
