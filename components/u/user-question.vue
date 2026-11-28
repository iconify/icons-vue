<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5fzpab0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5fzpab0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:user-question" /></template>
