<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z74esbcjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z74esbcjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:player-pause-fill" /></template>
