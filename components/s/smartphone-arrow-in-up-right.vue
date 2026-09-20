<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ov4x-iwjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ov4x-iwjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-up-right" /></template>
