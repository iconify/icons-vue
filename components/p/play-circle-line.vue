<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3z640blx.css';
import '../../css/k/k4dbl06su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3z640blx"/><path class="k4dbl06su"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:play-circle-line" /></template>
