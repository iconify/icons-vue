<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tznf3czua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tznf3czua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:pumpkin-filled" /></template>
