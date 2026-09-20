<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm5p7nbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm5p7nbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:philippine-peso" /></template>
