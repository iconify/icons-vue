<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kok5zc6gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kok5zc6gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:programming-bold" /></template>
