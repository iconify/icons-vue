<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik13m2b0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik13m2b0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:yoga-line" /></template>
