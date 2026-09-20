<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmu9f6bki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bmu9f6bki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ventilation" /></template>
