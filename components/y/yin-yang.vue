<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcvyz99kw.css';
import '../../css/x/x3cg0r7yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcvyz99kw"/><path class="x3cg0r7yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:yin-yang" /></template>
