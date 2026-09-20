<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4fiz0l4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l4fiz0l4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-2-bold" /></template>
