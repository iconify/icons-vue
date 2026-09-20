<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7g73ppkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7g73ppkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:stop-mini-line" /></template>
