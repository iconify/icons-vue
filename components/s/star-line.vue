<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/idk2wblek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idk2wblek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-line" /></template>
