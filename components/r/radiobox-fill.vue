<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj4g-wbrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj4g-wbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:radiobox-fill" /></template>
