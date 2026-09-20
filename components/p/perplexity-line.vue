<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6r7whmnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r6r7whmnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:perplexity-line" /></template>
