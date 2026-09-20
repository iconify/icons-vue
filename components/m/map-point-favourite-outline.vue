<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-3hur0vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e-3hur0vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-favourite-outline" /></template>
