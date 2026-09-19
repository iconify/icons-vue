<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wafrj7bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wafrj7bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pencil-off" /></template>
