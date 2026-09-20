<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcfoa-bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcfoa-bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radiobox-fill" /></template>
