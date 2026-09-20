<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8gur4b9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8gur4b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trivago" /></template>
