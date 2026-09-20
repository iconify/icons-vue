<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ijvu4ybpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ijvu4ybpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:receipt" /></template>
