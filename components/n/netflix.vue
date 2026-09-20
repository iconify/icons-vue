<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcjjm57yw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fcjjm57yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:netflix" /></template>
