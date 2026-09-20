<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3a39im_l.css';
import '../../css/t/tp_oyib9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3a39im_l"/><path class="tp_oyib9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:trello-board-line" /></template>
