<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1eqb3bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1eqb3bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:truck-arrow-up" /></template>
