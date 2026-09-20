<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_nx_3bwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_nx_3bwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:pencil-line" /></template>
