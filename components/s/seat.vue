<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fa85g3b0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fa85g3b0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:seat" /></template>
