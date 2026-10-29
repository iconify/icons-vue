<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u5u0dpbwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u5u0dpbwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:puzzle-piece" /></template>
