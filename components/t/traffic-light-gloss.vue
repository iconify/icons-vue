<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp9ph3m6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp9ph3m6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:traffic-light-gloss" /></template>
