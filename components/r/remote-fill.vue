<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py8mnxb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py8mnxb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:remote-fill" /></template>
