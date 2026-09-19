<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_nerh3_q.css';
import '../../css/r/rdl-cintb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_nerh3_q"/><path class="rdl-cintb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:monitor-wallpaper" /></template>
