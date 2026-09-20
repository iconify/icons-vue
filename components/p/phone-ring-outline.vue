<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpoa-6mah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpoa-6mah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:phone-ring-outline" /></template>
