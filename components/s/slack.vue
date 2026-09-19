<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxkfan9rf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxkfan9rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:slack" /></template>
