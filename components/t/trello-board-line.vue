<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alqykkbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alqykkbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trello-board-line" /></template>
