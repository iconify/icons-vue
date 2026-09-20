<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idh6qysuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idh6qysuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:to-do-fill" /></template>
