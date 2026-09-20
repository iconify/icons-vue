<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvq5z1btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qvq5z1btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:play-football-fill" /></template>
