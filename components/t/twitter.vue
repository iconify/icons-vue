<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7nb4_1cw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7nb4_1cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:twitter" /></template>
