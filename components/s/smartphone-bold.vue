<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct4cg4b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ct4cg4b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-bold" /></template>
