<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3___g9xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3___g9xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:mic-2-ai-line" /></template>
