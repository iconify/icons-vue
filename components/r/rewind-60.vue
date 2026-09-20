<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1c0ct14k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i1c0ct14k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rewind-60" /></template>
