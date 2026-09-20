<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcsh3jbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcsh3jbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sticker-check" /></template>
