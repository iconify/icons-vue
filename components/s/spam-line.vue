<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydlepfb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydlepfb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spam-line" /></template>
