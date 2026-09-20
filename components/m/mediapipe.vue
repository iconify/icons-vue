<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8xnl5bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8xnl5bll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mediapipe" /></template>
