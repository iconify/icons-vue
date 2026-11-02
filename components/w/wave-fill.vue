<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kx53cu8on.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kx53cu8on"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:wave-fill" /></template>
