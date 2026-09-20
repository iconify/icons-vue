<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s75etwb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s75etwb0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ticket-tailor" /></template>
