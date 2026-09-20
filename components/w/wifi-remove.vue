<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcn2f7bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rcn2f7bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-remove" /></template>
