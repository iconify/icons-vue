<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inn4uxbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="inn4uxbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:pexels" /></template>
