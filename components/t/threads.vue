<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th7y1ob8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th7y1ob8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:threads" /></template>
