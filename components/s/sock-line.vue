<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j48fsi5yx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j48fsi5yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sock-line" /></template>
