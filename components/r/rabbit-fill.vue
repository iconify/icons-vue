<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo5l02dsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fo5l02dsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rabbit-fill" /></template>
