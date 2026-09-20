<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_5qt8t0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_5qt8t0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wireless-charging-fill" /></template>
