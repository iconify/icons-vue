<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jph56f29d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jph56f29d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:table-2-line" /></template>
