<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j-mm7tj2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-mm7tj2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlock-line" /></template>
