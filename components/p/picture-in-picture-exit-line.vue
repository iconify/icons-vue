<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i8w9k1b8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8w9k1b8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:picture-in-picture-exit-line" /></template>
