<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl8g6mbul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl8g6mbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:w-3-schools" /></template>
