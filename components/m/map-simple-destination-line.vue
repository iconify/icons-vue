<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d51d4d4ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d51d4d4ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:map-simple-destination-line" /></template>
