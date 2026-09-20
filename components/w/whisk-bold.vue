<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu8v03boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vu8v03boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whisk-bold" /></template>
