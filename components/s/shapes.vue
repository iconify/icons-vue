<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9l0w07um.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9l0w07um"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:shapes" /></template>
