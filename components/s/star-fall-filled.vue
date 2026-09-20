<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzi9wnb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzi9wnb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:star-fall-filled" /></template>
