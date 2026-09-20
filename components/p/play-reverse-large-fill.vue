<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx17bi-cs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx17bi-cs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-reverse-large-fill" /></template>
