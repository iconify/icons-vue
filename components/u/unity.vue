<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqnlv9cha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqnlv9cha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:unity" /></template>
