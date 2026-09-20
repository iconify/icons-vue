<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwj-4kzzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwj-4kzzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:read" /></template>
