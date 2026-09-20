<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c00g-56-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c00g-56-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ticket-fill" /></template>
