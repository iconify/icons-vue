<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt3q6bctu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt3q6bctu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:spa" /></template>
