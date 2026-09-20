<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn402ibbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn402ibbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:moon-fill" /></template>
