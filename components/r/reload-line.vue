<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpfpg0b7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gpfpg0b7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:reload-line" /></template>
