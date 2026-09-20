<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jasc9ibwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jasc9ibwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-play" /></template>
