<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5qyh6gwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z5qyh6gwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:perplexity-fill" /></template>
