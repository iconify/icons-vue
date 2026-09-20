<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hl0zvbbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hl0zvbbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paint-roller" /></template>
