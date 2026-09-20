<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj0zc8r9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pj0zc8r9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:presentation-play" /></template>
