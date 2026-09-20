<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/syl5sxbgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syl5sxbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:numeric-6-boxes-outline" /></template>
