<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-6y14npf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u-6y14npf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-alt-arrow-down-bold" /></template>
