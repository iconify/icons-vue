<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy0--mhdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xy0--mhdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-right-outline" /></template>
