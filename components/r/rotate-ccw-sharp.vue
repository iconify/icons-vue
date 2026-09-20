<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwxl1lh0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwxl1lh0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-ccw-sharp" /></template>
