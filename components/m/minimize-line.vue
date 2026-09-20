<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fj1v9refi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj1v9refi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:minimize-line" /></template>
