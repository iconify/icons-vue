<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jwzh7abjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwzh7abjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:square-scissors" /></template>
