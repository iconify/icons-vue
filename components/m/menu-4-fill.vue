<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knso19jju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knso19jju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-4-fill" /></template>
