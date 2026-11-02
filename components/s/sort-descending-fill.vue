<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tuqw8uppp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuqw8uppp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sort-descending-fill" /></template>
