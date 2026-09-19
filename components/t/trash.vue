<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grrnzpbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="grrnzpbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:trash" /></template>
