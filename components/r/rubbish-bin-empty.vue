<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-lyb0boe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-lyb0boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:rubbish-bin-empty" /></template>
