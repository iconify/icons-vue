<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqb70dbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vqb70dbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:waving-hand-remix" /></template>
