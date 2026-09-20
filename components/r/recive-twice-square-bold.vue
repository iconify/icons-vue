<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci6l0phtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ci6l0phtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:recive-twice-square-bold" /></template>
