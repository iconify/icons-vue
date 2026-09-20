<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjajlikcf.css';
import '../../css/q/q4b6bxbog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sjajlikcf"/><path class="q4b6bxbog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:train-fill" /></template>
