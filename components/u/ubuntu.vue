<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f7m1x7-2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7m1x7-2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ubuntu" /></template>
