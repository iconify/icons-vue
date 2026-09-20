<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/buyn88y-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="buyn88y-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:star-s-fill" /></template>
