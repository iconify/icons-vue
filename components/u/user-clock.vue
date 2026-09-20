<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chg7ycchf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chg7ycchf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:user-clock" /></template>
