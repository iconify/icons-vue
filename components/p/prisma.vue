<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q13ynob0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q13ynob0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:prisma" /></template>
