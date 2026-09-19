<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1h9l5vao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="u1h9l5vao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:unread" /></template>
