<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j84o_8b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j84o_8b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trello-board-fill" /></template>
