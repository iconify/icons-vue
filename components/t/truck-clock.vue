<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmhhk40sw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmhhk40sw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:truck-clock" /></template>
