<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2keqxlad.css';
import '../../css/c/cbeuwxbbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2keqxlad"/><path class="cbeuwxbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:room" /></template>
