<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e24o_d0ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e24o_d0ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:text-to-speech" /></template>
