<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7dhy-buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7dhy-buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:menu-2-line" /></template>
