<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cla-b3b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cla-b3b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:square-medium" /></template>
