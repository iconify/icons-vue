<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-uyr0b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-uyr0b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mental-health-fill" /></template>
