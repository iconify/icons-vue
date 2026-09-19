<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjk_cab6w.css';
import '../../css/u/u7j1z5bkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjk_cab6w"/><path class="u7j1z5bkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:oven-filled" /></template>
