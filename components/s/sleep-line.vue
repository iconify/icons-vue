<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yb0m9_28x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb0m9_28x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sleep-line" /></template>
