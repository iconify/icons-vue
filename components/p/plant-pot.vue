<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urb91x35d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urb91x35d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:plant-pot" /></template>
