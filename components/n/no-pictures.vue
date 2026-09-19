<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9aio8bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9aio8bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:no-pictures" /></template>
