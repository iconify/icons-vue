<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tjvn8-bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjvn8-bgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-2-line" /></template>
