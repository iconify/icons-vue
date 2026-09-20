<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkl9mhbcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkl9mhbcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pen-ai-fill" /></template>
