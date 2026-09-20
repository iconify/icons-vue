<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x27tik33z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x27tik33z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:screen-bold" /></template>
