<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxkzqccrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxkzqccrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:module-puzzle-2" /></template>
