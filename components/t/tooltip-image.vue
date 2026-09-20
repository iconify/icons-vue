<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/le-9h2bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le-9h2bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tooltip-image" /></template>
