<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulin1z6mh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulin1z6mh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safe-box-line" /></template>
