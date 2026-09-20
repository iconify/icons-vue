<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/auyavi8jz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="auyavi8jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:truck-filled" /></template>
