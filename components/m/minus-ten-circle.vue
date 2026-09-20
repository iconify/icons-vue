<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgz8urb_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zgz8urb_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:minus-ten-circle" /></template>
