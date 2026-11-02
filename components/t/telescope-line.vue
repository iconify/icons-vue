<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j70zj18xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j70zj18xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:telescope-line" /></template>
