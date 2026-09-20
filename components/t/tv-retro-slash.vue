<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o60ci1m4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o60ci1m4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:tv-retro-slash" /></template>
