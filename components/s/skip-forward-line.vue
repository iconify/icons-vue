<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ok38s20xq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ok38s20xq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:skip-forward-line" /></template>
