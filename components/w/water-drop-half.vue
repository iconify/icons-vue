<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq9_pobzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq9_pobzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:water-drop-half" /></template>
