<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imy963b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imy963b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:tailwind-css" /></template>
