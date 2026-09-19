<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edm9wy9_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edm9wy9_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ppt-01" /></template>
