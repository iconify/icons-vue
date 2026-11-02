<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lh0mm2bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh0mm2bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:suitcase-fill" /></template>
