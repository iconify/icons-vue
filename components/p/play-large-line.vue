<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prb1s5poo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prb1s5poo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:play-large-line" /></template>
