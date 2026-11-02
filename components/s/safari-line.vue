<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/toptlzn0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="toptlzn0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safari-line" /></template>
