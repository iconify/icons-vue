<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p-k55vb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-k55vb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:table-line" /></template>
