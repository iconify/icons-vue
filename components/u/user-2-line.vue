<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwf6w8c0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iwf6w8c0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-2-line" /></template>
