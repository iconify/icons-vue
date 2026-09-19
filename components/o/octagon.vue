<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fm5wy70iv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm5wy70iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:octagon" /></template>
