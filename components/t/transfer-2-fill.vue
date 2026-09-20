<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c22f3xb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c22f3xb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:transfer-2-fill" /></template>
