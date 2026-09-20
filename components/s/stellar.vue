<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv_otkb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv_otkb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:stellar" /></template>
