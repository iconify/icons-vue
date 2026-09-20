<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jph_z1b8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jph_z1b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sun-wireless" /></template>
