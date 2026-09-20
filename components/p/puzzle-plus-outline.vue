<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy8j9sb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy8j9sb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:puzzle-plus-outline" /></template>
