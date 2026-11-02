<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py5cczbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="py5cczbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thunderstorm-line" /></template>
