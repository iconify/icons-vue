<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqz39y55m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqz39y55m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:shapes" /></template>
