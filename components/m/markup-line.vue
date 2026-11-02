<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4x38p0ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4x38p0ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:markup-line" /></template>
