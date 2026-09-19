<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftayt_bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftayt_bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:repeat-alt-2" /></template>
