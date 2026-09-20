<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr3vqhb6h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pr3vqhb6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stop-circle-fill" /></template>
