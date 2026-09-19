<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1rfrbc2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="y1rfrbc2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-stop" /></template>
