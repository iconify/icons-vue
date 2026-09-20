<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-4k6nraj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w-4k6nraj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-italic-outline" /></template>
