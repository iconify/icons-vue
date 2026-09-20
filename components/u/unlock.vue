<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvixkob-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvixkob-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:unlock" /></template>
