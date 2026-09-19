<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3o3mjbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3o3mjbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tailwindcss" /></template>
