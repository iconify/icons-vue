<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjlt7px2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjlt7px2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:twitch-fill" /></template>
