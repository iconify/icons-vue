<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj70rrbfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj70rrbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:train-2-fill" /></template>
